# darknet_jetson_orin
- This repository involves instructions for building darknet on Jeson AGX Orin Developer Kit
- Instead of providing step by step instructions, only the "makefile" is provided in this repo
- The some modifications have been made in the "makefile" and these changes are labeled in the "makefile"
- Note that the modifications may be different depending on your JetPack version (and hence CUDA and cuDNN) 
- In my case the the Jetpack version is 5.0.1 whose contents are available here:
  - https://developer.nvidia.com/embedded/jetpack-sdk-501dp
- Path to nvcc is updated too
  - https://stackoverflow.com/a/46110010
