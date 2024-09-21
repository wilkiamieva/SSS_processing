 # SSS_tools

Repository for various batch processing tools to work with Sound Source Separation (SSS) routines.

SSS pre-processing v1.0.0
This notebook addresses an issue with some sound source separation (SSS) routines in which the output files are truncated a few samples with each iteration, by appending silence samples as a buffer. This should be run before SSS processing.
Warning: A separate notebook (SSS post-processing) shall truncate the SSS output files to restore them to the original number of samples.

SSS post-processing v1.0.0
Warning: Audio files should be pre-processed before SSS with a separate notebook (SSS pre-processing).
This notebook truncates the SSS output files to the lenght of the original files. This should be run after SSS processing.
