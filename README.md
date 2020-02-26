# Lane-detection-with-EKF

## 注意-> https://ww2.mathworks.cn/help/driving/examples/visual-perception-using-monocular-camera.html
  - Notice that the findParabolicLaneBoundaries takes a function handle, validateBoundaryFcn. This example function is listed at the end of this example. Using this additional input lets you reject some curves based on the values of the a, b, c parameters. It can also be used to take advantage of temporal information over a series of frames by constraining future a, b, c values based on previous video frames.
  - 请注意，findParabolicLaneBoundaries具有函数句柄validateBoundaryFcn。 该示例函数在本示例的末尾列出。 使用此附加输入，可以基于a，b，c参数的值拒绝某些曲线。 通过基于先前的视频帧限制未来的a，b，c值，它也可以用于在一系列帧上利用时间信息。
