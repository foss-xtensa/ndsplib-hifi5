# HiFi5_NDSP
NatureDSP Library for HiFi 5,5e and 5s DSP cores

# The repo is organized as follows.

## xws:
  * Last stable release version of the NDSP containing two xws files.  
  * An xws each, for the library-kernels and the test-driver.
    Ex : HiFi5_VFPU_library_v310.xws & HiFi5_VFPU_demo_v310.xws

  * Building and executing the xws in Xtensa Xplorer is described in the API Reference Document. 
  * Detailed release documentation can be extracted from lib.xws/doc folder.

### Release v3.1.0 Brief: 
  * Release Date : Feb-2025.    
  * This release is incremental release on the top of the previous release V3.0.0
  * Update over previous releasE: Coefficient and state config functionality is added for certain kernels
  *	Library is tested on HiFi5s, HiFi5e and HiFi5 cores on both RJ2024.4 and RI2024.3 toolchanins. 
  * Few kernels are not supported on HiFi5 cores.
  * Please refer to Release Notes and Reference API document for more details. 
  * All testing and performance measurements have been done on xt-clang using RJ2024.4 version of the Xtensa Xplorer and tools.
  * Sanity testing has been done for backward compatibility on xt-clang using RI2024.3 version of the Xtensa Xplorer and tools.
  
###Known issues:
	* coefficient and state config functionality is added for bellow kernels: bkfirf, bqriirf_df1_nd, bqriirf_df2_nd, bqriirf_df2t_nd, however, the testdriver part is not yet updated for the same, testing is performed on very limited data set, 

## NDSP_HiFi5
This contains the source code along with make files that will build in linux environment.  

## doc folder
This contains help documentation on how to build the source code in linux and run the performance and functional regressions. 
