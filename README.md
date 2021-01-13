# photutils_diverging_epsf

The stars directory contains pickled stars created with epsf builder for use in the notebook. The notebook demonstrates the problem, where EPSFBuilder diverges with increasing iteration instead of converging. This behavior does not exist in photutils version < 0.7. It works as expected, where the EPSFBuilder converges with each iteration.
