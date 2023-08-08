# HiFi_5_NDSP
NatureDSP Library for HiFi 5 DSP cores

# The repo is organized as follows.

## xws:
  * Last stable release version of the NDSP containing two xws files.

  * An xws each, for the library-kernels and the test-driver.
    Ex : HiFi5_VFPU_Library_v2_0_0.xws & HiFi5_VFPU_Demo_v2_0_0.xws

  * Building and executing the xws in Xtensa Xplorer is described in the API Reference Document. 
  * Detailed release documentation can be extracted from lib.xws/doc folder.

### Release v2.0.0 Brief: 
  * Release Date : 15-Jan-2021.  
  * This release is targeted for xt-clang compiler, and has added support for imaging kernels.
  * All testing and performance measurements have been done on xt-clang using RI2020.5 version of the Xtensa Xplorer and tools.

## NDSP_HiFi5
This contains the source code along with make files that will build in linux environment.  

## doc folder
This contains help documentation on how to build the source code in linux and run the performance and functional regressions. 
