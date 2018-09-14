# Change Log
All notable changes to `bpp` will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [4.0.2] - 2018-09-14
### Fixed
 - When resuming from a checkpoint, additional future expected checkpoints were
   no longer created. This is fixed now
## [4.0.1] - 2018-08-30
### Added
 - Scaling option in control file that prevents numerical underflow when
   calculating partial likelihoods
### Fixed
 - Fixed qsort callback function in A00 summary to adher to BSD qsort