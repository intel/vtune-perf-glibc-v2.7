DISCONTINUATION OF PROJECT.

This project will no longer be maintained by Intel.

Intel has ceased development and contributions including, but not limited to, maintenance, bug fixes, new releases, or updates, to this project. 

Intel no longer accepts patches to this project.

If you have an ongoing need to use this project, are interested in independently developing it, or would like to maintain patches for the open source software community, please create your own fork of this project. 
# The GNU C Library for Intel(R) VTune(TM) Amplifier Perf tool

This repository contains GNU C Library [sources](https://www.gnu.org/software/libc/sources.html) required for building [Intel(R) VTune(TM) Amplifier Perf tool](https://github.com/intel/vtune-perf-v4.3.1) employed by [Intel(R) VTune(TM) Amplifier](https://software.intel.com/en-us/vtune). See the Intel(R) VTune(TM) Amplifier documentation for more [information](https://software.intel.com/en-us/vtune-amplifier-help-driverless-event-based-sampling-collection) regarding Linux* Perf based analysis capabilities and configuration.

The GNU C Library [project](https://www.gnu.org/software/libc/) provides the core libraries for the GNU system and GNU/Linux* systems, as well as many other systems that use Linux* as the kernel. These libraries provide critical APIs including ISO C11, POSIX.1-2008, BSD, OS-specific APIs and more. These APIs include such foundational facilities as open, read, write, malloc, printf, getaddrinfo, dlopen, pthread_create, crypt, login, exit and more.

## Technical support

You may report your Intel(R) VTune(TM) Amplfier related technical issues and get some level of support at the official [VTune forum](https://software.intel.com/en-us/forums/intel-vtune-amplifier).

## Software license

GNU C Library is distributed under GNU Lesser General Public License, v.2.1. You can find full text of the license in the files at the root of source packages.

## Repository structure

The master branch contains this README.md file. The release branches are named like `amplxe_<major>_u<update>` (e.g., `amplxe_2019_u3`) and provide library source code for the corresponding VTune Perf tool releases.

## Contribution

Consider [this](https://www.gnu.org/software/libc/involved.html) to get involved.

## Team contacts

Feel free to send us [e-mail](mailto:alexey.budankov@intel.com).

------------------------------------------------------------------------
Intel and the Intel logo are trademarks of Intel Corporation or its subsidiaries in the U.S. and/or other countries.

\* Other names and brands may be claimed as the property of others.

