# terminator-arkit-demo
Short hacky demo for a Terminator UI with ARKit

Every detected face (Vision framework) is overlayed with a "TERMINATE" text. The code is from this tutorial: [Live Face Detection with ARKit and Vision Framework](https://medium.com/@Yanni_P/ios-tutorial-live-face-detection-with-arkit-and-vision-frameworks-dab62305cd0e).

This is a very HACKY proof of concept project! Using a timer is maybe not the best solution but it works, doing the detection in the `render:updateAtTime` function was unusable. 
