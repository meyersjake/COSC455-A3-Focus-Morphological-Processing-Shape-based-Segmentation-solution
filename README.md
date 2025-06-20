# COSC455-A3-Focus-Morphological-Processing-Shape-based-Segmentation-solution

Download Here: [COSC455 A3 Focus: Morphological Processing, Shape-based Segmentation solution](https://jarviscodinghub.com/assignment/a3-focus-morphological-processing-shape-based-segmentation-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. [7 points]: Consider the binary image ? and the structuring element ? below. Do the following by hand
(don’t use a computer):
a. Label the 4-connected components in ?.
b. Label the 8-connected components in ?.
c. Find the output of morphologically opening ? with ? – assume the origin of ? is at its center.
d. Find the output of morphologically closing ?
? with ?̂, where ?
?
is the background.
e. Using the results from (c) and (d) above, show that opening and closing are duals of each
other, i.e., (? ∘ ?)
? = (?
?
 ?̂). (an explanation with few words will do).
?
0 0 0 0 0 0 0 0 0 0
0 1 1 1 0 0 1 0 0 0
0 0 1 1 0 1 0 1 0 0
0 1 1 0 0 0 0 1 0 0
0 0 1 0 0 0 1 0 0 0
0 0 0 1 0 0 1 0 1 0
0 0 0 1 1 0 0 1 1 0
0 0 0 1 1 1 0 0 0 0
0 0 0 0 1 1 0 0 0 0
0 0 0 0 0 0 0 0 0 0
?
1
1
1
Marking guide:
+1 for a,b,e
+2 for c,d
2. [10 Points] Download the image ‘coop.png’ from Connect, then implement a morphology-based
algorithm in Matlab that does the following:
a. Count the “small circles”, “big circles”, “eggs”, and “chicken”. Display the count as the title of
the output image (see example below).
b. Mark the centers of the eggs and draw a bounding box around them.
The output should be as shown below.
Marking guide:
+8 for (a): 2 points for
each class of objects.
+2 for (b).
3. [10 points]: Download the image ‘money.png’ from Connect, then implement a morphology-based
algorithm in Matlab to compute and display the amount of money in $ in the image. The output
should be as shown below.
Marking guide:
+2 for breaking up the
image into coins
+3 for segmenting based on
coin types (+1 for each
type of coins)
+3 for computations based
on the coin type
4. [13 points] [Adapted from Gonzales textbook Q9.36]: A preprocessing step in an application of microscopy is
concerned with the issue of isolating individual round particles from similar particles that overlap in
groups of two or more particles (see following image – available on Connect as ‘particles.png’).
Assuming that particles have between 230 to 275 pixels per particle:
(a) Implement in Matlab an algorithm that uses “Connected Component Analysis” to produce three
images consisting respectively of
 Only of particles that have merged with the boundary of the image.
 Only overlapping particles.
 Only nonoverlapping particles.
(b) Extend your Matlab program so that it merges the above three image into one colored image that
displays the three classes of particles in three different colors (see example below).
Marking guide:
+9 for segmenting based
on particle (+3 for each
type)
+2 for generating and
displaying three
grayscale images.
+2 for the color image.
Note the following:
 Don’t dilate, erode, open, or close the given image.
 To build the colored final image, use the grayscale images as the three RGB components. Refer to
the course’s intro to Matlab lecture notes to see how to build a 3D array from several 2D arrays.
 Useful Matlab functions: padarray, find, cat.
5. [10 points]: Download the image ‘445_descr.png’ from Connect. Implement a morphology-based
algorithm in Matlab that will split the given image into two: one with the text only and one with the
background only. The output should be similar to the images below.
445_descr.png

Text only Background only
Marking guide:
+6 for extracting and displaying the background
+4 for extracting and displaying the text
Submission Instructions
1- Solve Q1 on paper and submit as scanned document or in Word/Excel/or similar program
and submit as a document file.
2- For each question Q2 to Q4, write a separate Matlab program or function.
3- Submit everything as one zip file to Blackboard Connect. Note that you can resubmit an
assignment, but the new submission overwrites the old submission and receives a new
timestamp.



