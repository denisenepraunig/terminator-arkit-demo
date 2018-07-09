# terminator-arkit-demo
Short hacky demo for a Terminator UI with ARKit: [Tweet](https://twitter.com/denisenepraunig/status/1016406960319672321?s=21).

Demo inspired by the original Terminator UI:

![Terminator UI](http://2.bp.blogspot.com/-c4Zp2vg_atY/Vb4ZW6GXSbI/AAAAAAAACwM/JUPaeZtDHJU/s1600/terminator_vision-550x235.jpg)

Current implemented UI (image from here: [huffpost.com](http://i.huffpost.com/gen/1044790/thumbs/o-CHUCK-NORRIS-facebook.jpg):

![Terminator Demo UI](./chuck-norris.png)

Every detected face (Vision framework) is overlayed with a "TERMINATE" text (not much ARKit functionallity used yet 🙈). The code is from this tutorial: [Live Face Detection with ARKit and Vision Framework](https://medium.com/@Yanni_P/ios-tutorial-live-face-detection-with-arkit-and-vision-frameworks-dab62305cd0e).

This is a very HACKY proof of concept project! Using a timer is maybe not the best solution but it works, doing the detection in the `render:updateAtTime` function was unusable. 

Next steps could be using Machine Learning models to predict gender and age like in the [FacesVisionDemo](https://github.com/cocoa-ai/FacesVisionDemo) or detecting objects with CoreML like in [CoreML-in-ARKit](https://github.com/hanleyweng/CoreML-in-ARKit). 
