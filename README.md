# HiFi5_NDSP
NatureDSP Library for HiFi 5,5e and 5s DSP cores

# The repo is organized as follows.

## xws:
  * Last stable release version of the NDSP containing two xws files.  
  * An xws each, for the library-kernels and the test-driver.
    Ex : HiFi5_VFPU_library_v300.xws & HiFi5_VFPU_demo_v300.xws

  * Building and executing the xws in Xtensa Xplorer is described in the API Reference Document. 
  * Detailed release documentation can be extracted from lib.xws/doc folder.

### Release v3.0.0 Brief: 
  * Release Date : Sept-2024.  
  * There are about 65 new kernels added.
  * This release is same as XPG release V3.0.0
  *	New kernels are soupported on HiFi5s, HiFi5e and HiFi5 cores on both RJ2024.3 and RI2023.11 toolchanins. 
  * Few kernels are not supported on HiFi5 cores.
  * Please refer to Release Notes and Reference API document for more details. 
  * All testing and performance measurements have been done on xt-clang using RJ2024.3 version of the Xtensa Xplorer and tools.
  * Sanity testing has been done for backward compatibility on xt-clang using RI2023.11 version of the Xtensa Xplorer and tools.

## NDSP_HiFi5
This contains the source code along with make files that will build in linux environment.  

## doc folder
This contains help documentation on how to build the source code in linux and run the performance and functional regressions. 
