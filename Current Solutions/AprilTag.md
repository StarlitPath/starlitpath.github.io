---
title: AprilTag
parent: Current Solutions
---

# AprilTag

Overall cost: Varies wildly. They recommend trying what you already have on hand before trying to go out and purchase a specific webcam for it. Only other cost is the printing out and DIY of the trackers themselves.

Requirements:
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

Thoughts:
* If you can get everything set up optimally, the tracking quality is impressive. See an example here: https://www.youtube.com/watch?v=Bngdi5zPxXc
* There is also MediaPipe which only requires a Webcam and a piece of software, but the requirements are different and it is a work-in-progress. Not recommended. Read up on it here: https://github.com/ju1ce/Mediapipe-VR-Fullbody-Tracking
