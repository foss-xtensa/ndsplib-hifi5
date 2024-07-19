# HiFi5_NDSP
NatureDSP Library for HiFi 5,5e and 5s DSP cores

# The repo is organized as follows.

## xws:
  * Last stable release version of the NDSP containing two xws files.

  * An xws each, for the library-kernels and the test-driver.
    Ex : HiFi5_VFPU_Library_v270.xws & HiFi5_VFPU_Demo_v270.xws

  * Building and executing the xws in Xtensa Xplorer is described in the API Reference Document. 
  * Detailed release documentation can be extracted from lib.xws/doc folder.

### Release v2.7.0 Brief: 
  * Release Date : Jul-2024.  
  * This release contains several new kernels to support complex vector operations and statistical computations 
  * Please refer to Release Notes and Reference API document for more details. 
  * All testing and performance measurements have been done on xt-clang using RJ2024.3 version of the Xtensa Xplorer and tools.
  * Sanity testing has been done for backward compatibility on xt-clang using RI2023.11 version of the Xtensa Xplorer and tools.

## NDSP_HiFi5
This contains the source code along with make files that will build in linux environment.  

## doc folder
This contains help documentation on how to build the source code in linux and run the performance and functional regressions. 
