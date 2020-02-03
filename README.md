# RTSP_Unity_Plugin
A RTSP Unity Plugin for Textures and Cameras

Downloaded the ffmpeg-4.2.2-win64-dev from https://ffmpeg.zeranoe.com/builds/ and add those as dependencies or copy them (include & lib) to the project folder.

Inside `RTSPUnityPluginSingleton.cpp` add `#pragma warning(disable : 4996)`,
Then build.

The default settings will place the resulting dll in ../../build/

Worked for me with VS2015 & Windows 10 SDK 
