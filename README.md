# Python-Hand-Detection-Finger-Counting

A second-year Computer Science & Electrical Engineering , I took the time between semesters to improve myself and my skills in image processing.
This project is my first experience in the field, a relatively basic and short project but incorporates some principles in image processing. Principles I learned in a course I took outside of university.

Detect Hand and count number of fingers using Convex Hull algorithm in OpenCV lib in Python

Steps Involved
1.Find the region of interest 2.Perform a Gaussian blur 4.Perform a Threshold 5.Find the Biggest Contour 6.Perform a convexHull 7.Count the no. of fingers

Convex Hull
In order to detect fingertips, we are going to use the Convex Hull technique. In mathematics, Convex Hull is the smallest convex set that contains a set of points. And a convex set is a set of points such that, if we trace a straight line from any pair of points in the set, that line must be also be inside the region. The result is then a nice, smooth region, much easier to be analysed than our contour, that contains many imperfections.


Based on: -https://en.wikipedia.org/wiki/Convex_hull_algorithms
          -https://arxiv.org/ftp/arxiv/papers/1312/1312.7560.pdf
