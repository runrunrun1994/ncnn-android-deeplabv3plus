# ncnn-android-deeplabv3plus

The CODE fork form [https://github.com/nihui/ncnn-android-yolov5](https://github.com/nihui/ncnn-android-yolov5)

The Deeplabv3+ object Person Segmentation

this is a sample ncnn android project, it depends on ncnn library only

https://github.com/Tencent/ncnn

## how to build and run
### step1
https://github.com/Tencent/ncnn/releases

download ncnn-android-vulkan-lib.zip or build ncnn for android yourself

### step2
extract ncnn-android-vulkan-lib.zip into app/src/main/jni or change the ncnn path to yours in app/src/main/jni/CMakeLists.txt

### step3
open this project with Android Studio, build it and enjoy!

## Result
|Model|CPU|GPU|
|---|---|---|
|deeplabv3+|**434.59**ms|**454.16**ms|


|Original|Result|
|---|---|
|!(org1)[https://github.com/runrunrun1994/Image/blob/main/PersonSegmeantation/Android/pexels-photo-824109.jpg] |!(res1)[https://github.com/runrunrun1994/Image/blob/main/PersonSegmeantation/Android/pexels-photo-824109.png]|

