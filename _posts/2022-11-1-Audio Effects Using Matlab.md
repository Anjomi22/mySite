---
layout: posts
title: Audio Effects Using Matlab
show_date: true

---
EE 321 Systems and Signal Processing





Introduction:
	 This project was performed using Matlab to study Video Processing. The Matlab code produced manipulates the video files Project2_vid.mp4 and Project2_vid.mp4. The code created measures the average intensity of 3 channels, red, green, and blue. These channels were then plotted against the frame number to get a graph of channel intensity. 

Video Handling:
	The Code for reading in the video and finding the amount of pixels per fame is found in Figure 1. The Height and Width of each frame is 384x284 with 148 frames in the entire video. That is 109,056 pixels per frame and 16,140,288 pixels total throughout the whole video. 

Image Handling:
	We selected frame 60 for image handling, this frame has 109,056 pixels. The video has 3 channels, red, green, and blue. Figure 5 shows the frame selected, frame 60, and Figure 6 shows the Histogram of red intensity across the selected frame. The code for image handling and creating the histogram is shown in figure 2. 
<img src="{{andrewkirkwood.me}}/assets/images/profile.png" alt="">
<figcaption>My Head.</figcaption>
Channel Manipulation: 
	Figure 3 shows the code used to manipulate the different channels, red, green, and blue. The intensity of each channel was measured for each frame and plotted. The graphs showing the intensities can be found in figures 7, 8, and 9. 

<img src="{{andrewkirkwood.me}}/assets/images/profile.png" alt="">
<figcaption>Also my Head.</figcaption>


Longer Video Manipulation:
	Our second video, Project2_vid.mp4, was 18 seconds long, it has 541 frames and is 400x224 pixels big. Each frame is 89,600 pixels giving a total of 48,473,600 pixels throughout the entire video. The video was then manipulated in the same way as the short video to get the average channel intensity over the entire video. The graphs for red, green, and blue can be found in figures 10,11, and 12. Figure 9 shows a screen capture for frame 200. The code for this section can be found in Figure 4. 

Conclusion:
	Our matlab code manipulated 2 different videos for video processing. The average intensity of each channel, red, green and blue, was plotted for both videos. The results can be seen in the figures below. As expected, the values for each of these channels varied frame to frame. 



Figures:

Figure 1: Video Handling Code


Figure 2: Image Handing Code


Figure 3: Channel Manipulation Code


Figure 4: Longer Video Manipulation Code


Figure 5: Frame Selected for Image handling


Figure 6: Histogram of Red Intensity Across Frame 60


Figure 7: Red Intensity across the whole video


Figure 8: Green Intensity Across the Whole Video


Figure 8: Blue Intensity Across the Whole Video


Figure 9: Frame 200 from Video 2


Figure 10: Average Red Intensity Across the Whole Video


Figure 11: Average Green Intensity Across the Whole Video


Figure 12: Average Blue Intensity Across the Whole Video
