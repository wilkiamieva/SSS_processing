# SSS_tools

Repository various tools to work with for Sound Source Separation (SSS) routines.

SSS pre-processing v1.0.0
This notebook addresses an issue with some sound source separation (SSS) routines in which the output files are truncated a few samples with each iteration, by appending silence samples as a buffer. This should be run before SSS processing. A separate notebook (SSS post-processing) shall truncate the SSS output files to restore them to the original number of samples.

SSS post-processing v1.0.0
This notebook truncates the SSS output files to the original lenght. This should be run after SSS processing. Audio files should be pre-processed first with a separate notebook (SSS pre-processing).
