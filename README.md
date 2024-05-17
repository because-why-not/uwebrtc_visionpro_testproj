To test download the unity project here: https://github.com/because-why-not/uwebrtc_visionpro_testproj/releases

To build the plugins from scratch, please see https://github.com/because-why-not/uwebrtc_visionpro

The main branches do not include any binaries to reduce the size of the repository. Please see branches starting with v to checkout the binaries via LFS. 

The simulator plugin is built at `./Assets/webrtc/Runtime/Plugins/simxros/` and the 
device plugin at `./Assets/webrtc/Runtime/Plugins/xros~`

To switch from simulator to device plugin remove the ~ from "xros~" and append it to "simxros" in the folder names.
They cannot both be included into the project at the same time. 
