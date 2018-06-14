
Summary of object detection and instance segmentation implemented by Mask-RCNN. 

Demonstration Slices:
From Waleed Abdulla 's computer vision meetup
https://docs.google.com/presentation/d/1LjsylrgfGAo3s0n1GqCwPQ4rXdeHpcbJ8RWgaspKSw8 

The content is summarized also from his blog


To test on own data, it also provides an image annotator called VIA :
http://www.robots.ox.ac.uk/~vgg/software/via/

As for the main problem of my previous nuclei segmentation, cells in HPC region are so close to each other and hard to separate by using the traditional CV methods. So I hope we can use this annotator to label the polygon/ellipsoid region to solve the cell clumps segmentation.
To sum up, I am suggesting replacing our previous bbox labeling with polygon/ellipsoid region labeling.
