.. _secrng:

**************
AOCL SecureRNG
**************

Introduction
============
The AOCL-SecureRNG Library exposes APIs to access hardware generated random numbers
using x86 instructions RDRAND and RDSEED.


Installation
============

AOCL-SecureRNG library installable package is available `here
<https://www.amd.com/en/developer/aocl.html>`_.
Linux & Windows installer pacakges are available for download.
Source code for AOCL-SecureRNG is opensource and released with installer package.


Secure RNG
==========

`Whitepaper
<https://www.amd.com/content/dam/amd/en/documents/pdfs/developer/aocl/
amd-secure-random-number-generator-library-2.0-whitepaper.pdf>`_
provide details on AMD Secure Random Number Generator (Secure RNG) library
which provides an easy-to-use software APIs to access random number generated AMD's
hardware RNG implementation.


.. _secrng_example_:

SecureRNG Example
-----------------

.. code-block:: c

    /* Check for RDRAND instruction support */
    int ret = is_RDRAND_supported();
    int N = 1000;

    /* If RDRAND supported */
    if (ret == SECRNG_SUPPORTED) {
      uint64_t rng64;

      /* Get 64-bit random number */
      ret = get_rdrand64u(&rng64, 0);

      if (ret == SECRNG_SUCCESS)
        printf("RDRAND rng 64-bit value %lu\n\n", rng64);
      else
        printf("Failure in retrieving random value using RDRAND!\n");

      /* Get a range of 64-bit random values */
      uint64_t* rng64_arr = (uint64_t*) malloc(sizeof(uint64_t) * N);

      ret = get_rdrand64u_arr(rng64_arr, N, 0);

      if (ret == SECRNG_SUCCESS) {
        printf("RDRAND for %u 64-bit random values succeeded!\n", N);
        printf("First 10 values in the range : \n");

        for (int i = 0; i < (N > 10? 10 : N); i++)
          printf("%lu\n", rng64_arr[i]);
      } else
          printf("Failure in retrieving array of random values using RDRAND!\n");
    } else {
        printf("No support for RDRAND!\n");
    }


.. End of Doc
