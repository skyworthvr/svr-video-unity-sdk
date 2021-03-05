# 1.3.5 (2021-01-07)
* Update base SDK
# 1.3.4 (2020-11-12)
* 立体控制  
  Shader keywords : **USE_STEREO**
# 1.3.3 (2020-07-27)
* Update base SDK
* 切换清晰度接口  
```csharp
/// <summary>
/// Used to switch between different video sources during playback, you can be used to switch resolutions. 
/// The video will automatically play after switching.
/// </summary>
/// <param name="path">video address</param>
/// <param name="time">start time</param>
public void SwitchResolution(string path,int time)
```
# 1.3.2 (2020-06-22)
* Update base SDK
# 1.3.1 (2020-03-06)
* Update base SDK
# 1.3.0 (2020-02-19)
* 支持立体格式CubeMap的视频  
  需要使用SvrVideoUnlitShaderForMultiViewCubeMap.shader
# 1.2.8 (2019-09-17)
* Fixed bug
* Added decryption method to play encrypted video.
# 1.2.6 (2019-07-05)
* update rtsp/other live config
# 1.2.5 (2019-06-14)
* Update library files, modify memory usage. Update player video uri. Add no-singlepass shader.
# 1.2.4 (2019-05-23)
* Fixed bug
# 1.2.3 (2018-12-28)
* Fixed bug
# 1.2.2 (2018-12-12)
* Fixed bug
# 1.2.1 (2018-12-06)
* Fixed bug
# 1.2.0 (2018-11-22)