---
layout: post
title: Skeleton <br><font style="color:gray"><small>Machine Learning Program</small></font>
description: Lorem Ipsum is simply dummy text
summary: Reimagining remote desktop by transmitting structured OCR data instead of streaming raw video..<br><br><strong>Written:</strong> JAVA, YOLO (Real-Time Object Detection), Google's Tesseract OCR, Machine Learning, NetBeans
---
<style>
h1{
    color: Black;
}
</style>
Skeleton was developed at Yale University's 36-hour annual hackathon and was built by a four-person team — Michael Amay, Adam Wolnikowskie, Michael Vargas, and Evan Visher. The challenge, posed by Ivanti, was to explore how Machine Learning could be applied if a Remote Desktop application were redesigned from the ground up. Our solution aimed to replace traditional bitmap and video streaming with a smarter, data-driven alternative.

On the host machine, we captured live screen frames and processed them using OpenCV to isolate and identify UI regions within each frame. Those regions were then piped through Google's Tesseract OCR engine via Python and PyCharm, using the pytesseract wrapper to extract text and its positional metadata — bounding-box coordinates and layout structure. Each frame was serialized into a lightweight JSON payload and transmitted to the client. On the receiving end, the JSON was deserialized and each text element was reconstructed onto a canvas at its original coordinates, reproducing the host's screen without ever transmitting a raw image or video stream.

For text-heavy environments like terminals, documents, and code editors, this approach proved significantly more bandwidth-efficient than traditional streaming. The core pipeline — OpenCV for frame analysis, Tesseract for OCR, and Python tying it all together — kept the solution technically grounded while putting Machine Learning at the center of the capture process. That earned our team the Best Use of Machine Learning award at the event.
<p></p>
<span style="font-weight:900; margin: 0;">Technologies and Tools Used:</span>
Python, YOLO (Real-Time Object Detection), Google's Tesseract OCR, Machine Learning, PyCharm
<p></p>   

<a href="https://github.com/Michaelamay/Skeleton-1">View Source Code</a>

<!-- Image section -->

<!-- TODO: Recover predictions.png from i.ibb.co. <img src="https://i.ibb.co/tJKfsHN/predictions.png" alt="Skeleton predictions screen" border="3"> -->
<img src="{{ '/images/skeleton/group.jpg' | relative_url }}" alt="Skeleton project team" border="3">


