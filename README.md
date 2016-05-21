# Fattal02-HDR-ToneMapping
[Fattal02](http://www.cs.huji.ac.il/~danix/hdr/hdrc.pdf) HDR Tone mapping operator. Gradient Domain High Dynamic Range Compression.

**File Layout:**  
/dev/  
--/boost_1_61_0/  
--/fftw-3.3.4/  
/worksapce/  
--/FattalToneMapping/  
----/build/  
------/linux/  
--------compile.sh  
--------install_dev_env.sh  
------/vs2015/  
--/include/  
--/results/  
--/samples/  
--/src/  

**Usage:**  
./app HDRInputPath LDROutputPath [AlphaMultiplier] [Bheta] [S]

**Dependencies:**  
*[FFTW3](http://www.fftw.org/)  
*[OpenCV (>= 2.4.9)](http://opencv.org/downloads.html), note that OpenCV3 already have HDR Tone Mapping Operators  
*[Boost::multi_array (1.61.0)](http://www.boost.org/users/history/version_1_61_0.html)

**Default Cammand Line Parameters:**  
  alphamultiplier : 0.18  
  bheta : 0.87  
  s : 0.55
  
For Windows Visual Studio 2015 solution is under "build/vs2015/"  
