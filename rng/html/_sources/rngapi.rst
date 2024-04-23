.. _rngapi:

*********************
AOCL-RNG Library APIs
*********************

.. _rngversion_function_:

AOCL-RNG Version Function
-------------------------

get_rngversion()
~~~~~~~~~~~~~~~~
.. doxygenfunction:: GET_RNGVERSION
  :outline:
.. doxygenfunction:: get_rngversion_
  :outline:
.. doxygenfunction:: get_rngversion


.. _rnginit_functions_:

Initialization Functiontions
----------------------------

randinitialize()
~~~~~~~~~~~~~~~~
.. doxygenfunction:: SRANDINITIALIZE
  :outline:
.. doxygenfunction:: DRANDINITIALIZE
  :outline:
.. doxygenfunction:: srandinitialize_
  :outline:
.. doxygenfunction:: drandinitialize_
  :outline:
.. doxygenfunction:: srandinitialize
  :outline:
.. doxygenfunction:: drandinitialize


.. _mtgen_init_secrng_:

Initialize Mersenne Twister with SecureRNG
------------------------------------------

randinitialize_secrng()
~~~~~~~~~~~~~~~~~~~~~~~
.. doxygenfunction:: drandinitialize_secrng


.. _userbasegen_hooks_:

User's own Base Generator Hooks
-------------------------------

randinitializeuser()
~~~~~~~~~~~~~~~~~~~~
.. doxygenfunction:: SRANDINITIALIZEUSER
  :outline:
.. doxygenfunction:: DRANDINITIALIZEUSER
  :outline:
.. doxygenfunction:: srandinitializeuser_
  :outline:
.. doxygenfunction:: drandinitializeuser_
  :outline:
.. doxygenfunction:: srandinitializeuser
  :outline:
.. doxygenfunction:: drandinitializeuser
  :outline:
.. doxygentypedef:: RNG_DRANDINITIALIZEUSER_UINI
.. doxygentypedef:: RNG_DRANDINITIALIZEUSER_UGEN



.. _bbsgen_functions_:

Blum-Blum-Shub Generator Functions
----------------------------------

randinitializebbs()
~~~~~~~~~~~~~~~~~~~
.. doxygenfunction:: SRANDINITIALIZEBBS
  :outline:
.. doxygenfunction:: DRANDINITIALIZEBBS
  :outline:
.. doxygenfunction:: srandinitializebbs_
  :outline:
.. doxygenfunction:: drandinitializebbs_
  :outline:
.. doxygenfunction:: srandinitializebbs
  :outline:
.. doxygenfunction:: drandinitializebbs

randblumblumshub()
~~~~~~~~~~~~~~~~~~
.. doxygenfunction:: SRANDBLUMBLUMSHUB
  :outline:
.. doxygenfunction:: DRANDBLUMBLUMSHUB
  :outline:
.. doxygenfunction:: srandblumblumshub_
  :outline:
.. doxygenfunction:: drandblumblumshub_
  :outline:
.. doxygenfunction:: srandblumblumshub
  :outline:
.. doxygenfunction:: drandblumblumshub


.. _multistreamgen_functions_:

Multiple Streams Generator Functions
------------------------------------

randskipahead()
~~~~~~~~~~~~~~~
.. doxygenfunction:: SRANDSKIPAHEAD
  :outline:
.. doxygenfunction:: DRANDSKIPAHEAD
  :outline:
.. doxygenfunction:: srandskipahead_
  :outline:
.. doxygenfunction:: drandskipahead_
  :outline:
.. doxygenfunction:: srandskipahead
  :outline:
.. doxygenfunction:: drandskipahead

randleapfrog()
~~~~~~~~~~~~~~
.. doxygenfunction:: SRANDLEAPFROG
  :outline:
.. doxygenfunction:: DRANDLEAPFROG
  :outline:
.. doxygenfunction:: srandleapfrog_
  :outline:
.. doxygenfunction:: drandleapfrog_
  :outline:
.. doxygenfunction:: srandleapfrog
  :outline:
.. doxygenfunction:: drandleapfrog


.. _distributiongen_functions_:

Distribution Generator Functions
--------------------------------

.. _continuous_univariate_:

Continuous Univariate Distribution Functions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

randbeta()
^^^^^^^^^^
.. doxygenfunction:: SRANDBETA
  :outline:
.. doxygenfunction:: DRANDBETA
  :outline:
.. doxygenfunction:: srandbeta_
  :outline:
.. doxygenfunction:: drandbeta_
  :outline:
.. doxygenfunction:: srandbeta
  :outline:
.. doxygenfunction:: drandbeta

randcauchy()
^^^^^^^^^^^^
.. doxygenfunction:: SRANDCAUCHY
  :outline:
.. doxygenfunction:: DRANDCAUCHY
  :outline:
.. doxygenfunction:: srandcauchy_
  :outline:
.. doxygenfunction:: drandcauchy_
  :outline:
.. doxygenfunction:: srandcauchy
  :outline:
.. doxygenfunction:: drandcauchy

randchisquared()
^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDCHISQUARED
  :outline:
.. doxygenfunction:: DRANDCHISQUARED
  :outline:
.. doxygenfunction:: srandchisquared_
  :outline:
.. doxygenfunction:: drandchisquared_
  :outline:
.. doxygenfunction:: srandchisquared
  :outline:
.. doxygenfunction:: drandchisquared

randexponential()
^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDEXPONENTIAL
  :outline:
.. doxygenfunction:: DRANDEXPONENTIAL
  :outline:
.. doxygenfunction:: srandexponential_
  :outline:
.. doxygenfunction:: drandexponential_
  :outline:
.. doxygenfunction:: srandexponential
  :outline:
.. doxygenfunction:: drandexponential

randf()
^^^^^^^
.. doxygenfunction:: SRANDF
  :outline:
.. doxygenfunction:: DRANDF
  :outline:
.. doxygenfunction:: srandf_
  :outline:
.. doxygenfunction:: drandf_
  :outline:
.. doxygenfunction:: srandf
  :outline:
.. doxygenfunction:: drandf

randgamma()
^^^^^^^^^^^
.. doxygenfunction:: SRANDGAMMA
  :outline:
.. doxygenfunction:: DRANDGAMMA
  :outline:
.. doxygenfunction:: srandgamma_
  :outline:
.. doxygenfunction:: drandgamma_
  :outline:
.. doxygenfunction:: srandgamma
  :outline:
.. doxygenfunction:: drandgamma

randgaussian()
^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDGAUSSIAN
  :outline:
.. doxygenfunction:: DRANDGAUSSIAN
  :outline:
.. doxygenfunction:: srandgaussian_
  :outline:
.. doxygenfunction:: drandgaussian_
  :outline:
.. doxygenfunction:: srandgaussian
  :outline:
.. doxygenfunction:: drandgaussian

randlogistic()
^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDLOGISTIC
  :outline:
.. doxygenfunction:: DRANDLOGISTIC
  :outline:
.. doxygenfunction:: srandlogistic_
  :outline:
.. doxygenfunction:: drandlogistic_
  :outline:
.. doxygenfunction:: srandlogistic
  :outline:
.. doxygenfunction:: drandlogistic

randlognormal()
^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDLOGNORMAL
  :outline:
.. doxygenfunction:: DRANDLOGNORMAL
  :outline:
.. doxygenfunction:: srandlognormal_
  :outline:
.. doxygenfunction:: drandlognormal_
  :outline:
.. doxygenfunction:: srandlognormal
  :outline:
.. doxygenfunction:: drandlognormal

randstudentst()
^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDSTUDENTST
  :outline:
.. doxygenfunction:: DRANDSTUDENTST
  :outline:
.. doxygenfunction:: srandstudentst_
  :outline:
.. doxygenfunction:: drandstudentst_
  :outline:
.. doxygenfunction:: srandstudentst
  :outline:
.. doxygenfunction:: drandstudentst

randtriangular()
^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDTRIANGULAR
  :outline:
.. doxygenfunction:: DRANDTRIANGULAR
  :outline:
.. doxygenfunction:: srandtriangular_
  :outline:
.. doxygenfunction:: drandtriangular_
  :outline:
.. doxygenfunction:: srandtriangular
  :outline:
.. doxygenfunction:: drandtriangular

randuniform()
^^^^^^^^^^^^^
.. doxygenfunction:: SRANDUNIFORM
  :outline:
.. doxygenfunction:: DRANDUNIFORM
  :outline:
.. doxygenfunction:: sranduniform_
  :outline:
.. doxygenfunction:: dranduniform_
  :outline:
.. doxygenfunction:: sranduniform
  :outline:
.. doxygenfunction:: dranduniform

randvonmises()
^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDVONMISES
  :outline:
.. doxygenfunction:: DRANDVONMISES
  :outline:
.. doxygenfunction:: srandvonmises_
  :outline:
.. doxygenfunction:: drandvonmises_
  :outline:
.. doxygenfunction:: srandvonmises
  :outline:
.. doxygenfunction:: drandvonmises

randweibull()
^^^^^^^^^^^^^
.. doxygenfunction:: SRANDWEIBULL
  :outline:
.. doxygenfunction:: DRANDWEIBULL
  :outline:
.. doxygenfunction:: srandweibull_
  :outline:
.. doxygenfunction:: drandweibull_
  :outline:
.. doxygenfunction:: srandweibull
  :outline:
.. doxygenfunction:: drandweibull


.. _discrete_univariate_:

Discrete Univariate Distribution Functions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

randbinomial()
^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDBINOMIAL
  :outline:
.. doxygenfunction:: DRANDBINOMIAL
  :outline:
.. doxygenfunction:: srandbinomial_
  :outline:
.. doxygenfunction:: drandbinomial_
  :outline:
.. doxygenfunction:: srandbinomial
  :outline:
.. doxygenfunction:: drandbinomial

randgeometric()
^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDGEOMETRIC
  :outline:
.. doxygenfunction:: DRANDGEOMETRIC
  :outline:
.. doxygenfunction:: srandgeometric_
  :outline:
.. doxygenfunction:: drandgeometric_
  :outline:
.. doxygenfunction:: srandgeometric
  :outline:
.. doxygenfunction:: drandgeometric

randhypergeometric()
^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDHYPERGEOMETRIC
  :outline:
.. doxygenfunction:: DRANDHYPERGEOMETRIC
  :outline:
.. doxygenfunction:: srandhypergeometric_
  :outline:
.. doxygenfunction:: drandhypergeometric_
  :outline:
.. doxygenfunction:: srandhypergeometric
  :outline:
.. doxygenfunction:: drandhypergeometric

randnegativebinomial()
^^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDNEGATIVEBINOMIAL
  :outline:
.. doxygenfunction:: DRANDNEGATIVEBINOMIAL
  :outline:
.. doxygenfunction:: srandnegativebinomial_
  :outline:
.. doxygenfunction:: drandnegativebinomial_
  :outline:
.. doxygenfunction:: srandnegativebinomial
  :outline:
.. doxygenfunction:: drandnegativebinomial

randpoisson()
^^^^^^^^^^^^^
.. doxygenfunction:: SRANDPOISSON
  :outline:
.. doxygenfunction:: DRANDPOISSON
  :outline:
.. doxygenfunction:: srandpoisson_
  :outline:
.. doxygenfunction:: drandpoisson_
  :outline:
.. doxygenfunction:: srandpoisson
  :outline:
.. doxygenfunction:: drandpoisson

randdiscreteuniform()
^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDDISCRETEUNIFORM
  :outline:
.. doxygenfunction:: DRANDDISCRETEUNIFORM
  :outline:
.. doxygenfunction:: sranddiscreteuniform_
  :outline:
.. doxygenfunction:: dranddiscreteuniform_
  :outline:
.. doxygenfunction:: sranddiscreteuniform
  :outline:
.. doxygenfunction:: dranddiscreteuniform

randgeneraldiscrete()
^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDGENERALDISCRETE
  :outline:
.. doxygenfunction:: DRANDGENERALDISCRETE
  :outline:
.. doxygenfunction:: srandgeneraldiscrete_
  :outline:
.. doxygenfunction:: drandgeneraldiscrete_
  :outline:
.. doxygenfunction:: srandgeneraldiscrete
  :outline:
.. doxygenfunction:: drandgeneraldiscrete

randbinomialreference()
^^^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDBINOMIALREFERENCE
  :outline:
.. doxygenfunction:: DRANDBINOMIALREFERENCE
  :outline:
.. doxygenfunction:: srandbinomialreference_
  :outline:
.. doxygenfunction:: drandbinomialreference_
  :outline:
.. doxygenfunction:: srandbinomialreference
  :outline:
.. doxygenfunction:: drandbinomialreference

randgeometricreference()
^^^^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDGEOMETRICREFERENCE
  :outline:
.. doxygenfunction:: DRANDGEOMETRICREFERENCE
  :outline:
.. doxygenfunction:: srandgeometricreference_
  :outline:
.. doxygenfunction:: drandgeometricreference_
  :outline:
.. doxygenfunction:: srandgeometricreference
  :outline:
.. doxygenfunction:: drandgeometricreference

randhypergeometricreference()
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDHYPERGEOMETRICREFERENCE
  :outline:
.. doxygenfunction:: DRANDHYPERGEOMETRICREFERENCE
  :outline:
.. doxygenfunction:: srandhypergeometricreference_
  :outline:
.. doxygenfunction:: drandhypergeometricreference_
  :outline:
.. doxygenfunction:: srandhypergeometricreference
  :outline:
.. doxygenfunction:: drandhypergeometricreference

randnegativebinomialreference()
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDNEGATIVEBINOMIALREFERENCE
  :outline:
.. doxygenfunction:: DRANDNEGATIVEBINOMIALREFERENCE
  :outline:
.. doxygenfunction:: srandnegativebinomialreference_
  :outline:
.. doxygenfunction:: drandnegativebinomialreference_
  :outline:
.. doxygenfunction:: srandnegativebinomialreference
  :outline:
.. doxygenfunction:: drandnegativebinomialreference

randpoissonreference()
^^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDPOISSONREFERENCE
  :outline:
.. doxygenfunction:: DRANDPOISSONREFERENCE
  :outline:
.. doxygenfunction:: srandpoissonreference_
  :outline:
.. doxygenfunction:: drandpoissonreference_
  :outline:
.. doxygenfunction:: srandpoissonreference
  :outline:
.. doxygenfunction:: drandpoissonreference


.. _continuous_multivariate_:

Continuous Multivariate Distribution Functions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

randmultinormal()
^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDMULTINORMAL
  :outline:
.. doxygenfunction:: DRANDMULTINORMAL
  :outline:
.. doxygenfunction:: srandmultinormal_
  :outline:
.. doxygenfunction:: drandmultinormal_
  :outline:
.. doxygenfunction:: srandmultinormal
  :outline:
.. doxygenfunction:: drandmultinormal

randmultistudentst()
^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDMULTISTUDENTST
  :outline:
.. doxygenfunction:: DRANDMULTISTUDENTST
  :outline:
.. doxygenfunction:: srandmultistudentst_
  :outline:
.. doxygenfunction:: drandmultistudentst_
  :outline:
.. doxygenfunction:: srandmultistudentst
  :outline:
.. doxygenfunction:: drandmultistudentst

randmultinormalreference()
^^^^^^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDMULTINORMALREFERENCE
  :outline:
.. doxygenfunction:: DRANDMULTINORMALREFERENCE
  :outline:
.. doxygenfunction:: srandmultinormalreference_
  :outline:
.. doxygenfunction:: drandmultinormalreference_
  :outline:
.. doxygenfunction:: srandmultinormalreference
  :outline:
.. doxygenfunction:: drandmultinormalreference

randmultinormalr()
^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDMULTINORMALR
  :outline:
.. doxygenfunction:: DRANDMULTINORMALR
  :outline:
.. doxygenfunction:: srandmultinormalr_
  :outline:
.. doxygenfunction:: drandmultinormalr_
  :outline:
.. doxygenfunction:: srandmultinormalr
  :outline:
.. doxygenfunction:: drandmultinormalr

randmultistudentstreference()
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDMULTISTUDENTSTREFERENCE
  :outline:
.. doxygenfunction:: DRANDMULTISTUDENTSTREFERENCE
  :outline:
.. doxygenfunction:: srandmultistudentstreference_
  :outline:
.. doxygenfunction:: drandmultistudentstreference_
  :outline:
.. doxygenfunction:: srandmultistudentstreference
  :outline:
.. doxygenfunction:: drandmultistudentstreference

randmultistudentstr()
^^^^^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDMULTISTUDENTSTR
  :outline:
.. doxygenfunction:: DRANDMULTISTUDENTSTR
  :outline:
.. doxygenfunction:: srandmultistudentstr_
  :outline:
.. doxygenfunction:: drandmultistudentstr_
  :outline:
.. doxygenfunction:: srandmultistudentstr
  :outline:
.. doxygenfunction:: drandmultistudentstr


.. _discrete_multivariate_:

Discrete Multivariate Distribution Functions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

randmultinomial()
^^^^^^^^^^^^^^^^^
.. doxygenfunction:: SRANDMULTINOMIAL
  :outline:
.. doxygenfunction:: DRANDMULTINOMIAL
  :outline:
.. doxygenfunction:: srandmultinomial_
  :outline:
.. doxygenfunction:: drandmultinomial_
  :outline:
.. doxygenfunction:: srandmultinomial
  :outline:
.. doxygenfunction:: drandmultinomial


.. End of Doc
