---
title: Camera
parent: Solutions
---

# Camera
There are two versions of this solution:
* Camera + Print outs: This is the DIY solution requiring the printing of particular QR-code style markers for the purposes of your camera being able to track them. Requires making platforms out of cardboard or otherwise to place them on to then attach to your body like standard Trackers.
* Camera only: This is a not recommended but theoretically possible solution which uses your webcam alone to track your movements. This is not as effective as the Kinect method due to lacking a dedicated depth sensor.

You should not purchase a webcam or phone for this method without trying what you already have on hand, if you are wanting to try this method.

**Overall price:** Varies wildly depending on if you need to purchase a camera, the cost of doing the DIY if you want to do so, the printing of the QR-codes, etc..

### Option 1: AprilTag
This option uses the Camera + Print outs version of the solution.

This video is an example of a best case scenario for this Option: https://www.youtube.com/watch?v=Bngdi5zPxXc

#### Requirements:
* For detailed requirements, refer to here. The proper method requires much more setup than I could detail here. https://github.com/ju1ce/April-Tag-VR-FullBody-Tracker/wiki/Requirements
* Camera meeting the following specifications(as pulled from their wiki):
  * Resolution: A resolution of 720p is usually optimal. 480p can work, but you will have reduced range of detection.
  * FPS: While 60fps can help, it is not necessary. 30fps cameras are enough.
  * FOV: Any value will work, but low FOV cameras will reduce your playspace. 90° or more is preferred in order to cover your whole playspace if you put it into a corner.
  * The most important feature of your camera is MANUAL EXPOSURE CONTROL. Not having this feature means that your camera will have motion blur, which will break detection when you move.
* Alternatively, you can use an IPhone or Android Phone with a working app:
  * Apriltag recommended IPhone App: iOS Camera for OBS Studio
  * Apriltag recommended Android App: IP Webcam
* Apriltag Trackers Software: https://github.com/ju1ce/April-Tag-VR-FullBody-Tracker/releases
* Apriltag Trackers: https://github.com/ju1ce/April-Tag-VR-FullBody-Tracker/wiki/the-trackers
* Tolerance for DIY.

For Support: https://discord.gg/g2ctkXB4bb

### Option 2: MediaPipe or Driver4VR
This option uses only a Camera for the purposes of FBT.

#### Requirements:
* A good webcam, likely similar to the specs above. MediaPipe was created by the folks of AprilTag.
* The MediaPipe or Driver4VR software
  * MediaPipe(Free): https://github.com/ju1ce/Mediapipe-VR-Fullbody-Tracking
    * Support: https://discord.gg/g2ctkXB4bb
  * Driver4VR($17.99): https://store.steampowered.com/app/1366950/Driver4VR/
    * Support: https://support.driver4vr.com/
