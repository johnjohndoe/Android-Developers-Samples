BatchStepSensor
===============

This sample demonstrates the use of the two step sensors (step detector and counter) and sensor batching. It shows how to register a [SensorEventListener][1] with and without batching and shows how these events are received.

The Step Detector sensor fires an event when a step is detected, while the step counter returns the total number of steps since a listener was first registered for this sensor. Both sensors only count steps while a listener is registered.

This sample only covers the basic case, where a listener is only registered while the app is running. Likewise, batched sensors can be used in the background (when the CPU is suspended), which requires manually flushing the sensor event queue before it overflows, which is not covered in this sample.

---

* [Source][2]

[1]: http://developer.android.com/reference/android/hardware/SensorEventListener.html
[2]: http://developer.android.com/samples/BatchStepSensor/index.html
