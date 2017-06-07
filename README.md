# UnrealCapture
Unreal Capture Functionality Explorer

##### Capture Image:
Press ```Space``` to capture screenshot.

```Stat FPS``` in command console to show FPS info. 

```RenderTarget->ReadPixels``` and ```ENQUEUE_UNIQUE_RENDER_COMMAND_ONEPARAMETER``` Performance Test

Test machine:
```
Macbook Pro
2.5 GHz Intel Core i7
16 GB
NVIDIA GeForce GT 750m
```

Test result:
```
RenderTarget->ReadPixels
FPS: ~24fps, Frame: ~40ms

ENQUEUE_UNIQUE_RENDER_COMMAND_ONEPARAMETER
FPS: ~30fps, Frame: ~30ms
```
