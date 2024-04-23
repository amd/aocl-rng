.. _secrngapi:

***************************
AOCL-SecureRNG Library APIs
***************************

.. _secrngversion_api_:

AOCL-SecureRNG Version API
--------------------------

get_secrngversion()
^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: get_secrngversion


.. _secrng_rdrand_:

RDRAND Instruction
------------------

is_RDRAND_supported()
^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: is_RDRAND_supported

get_rdrand16u()
^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdrand16u

get_rdrand32u()
^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdrand32u

get_rdrand64u()
^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdrand64u

get_rdrand32u_arr()
^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdrand32u_arr

get_rdrand64u_arr()
^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdrand64u_arr

get_rdrand_bytes_arr()
^^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdrand_bytes_arr


.. _secrng_rdseed_:

RDSEED Instruction
------------------

is_RDSEED_supported()
^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: is_RDSEED_supported

get_rdseed16u()
^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdseed16u

get_rdseed32u()
^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdseed32u

get_rdseed64u()
^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdseed64u

get_rdseed32u_arr()
^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdseed32u_arr

get_rdseed64u_arr()
^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdseed64u_arr

get_rdseed_bytes_arr()
^^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: get_rdseed_bytes_arr


.. End of Doc
