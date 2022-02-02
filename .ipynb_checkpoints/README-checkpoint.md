# OCR, Facial Recognition, Computer Vision Project #

This project is based on an assignment that is part of [Course 5 of 5](https://www.coursera.org/learn/python-project) in the [Python 3 Programming Specialization](https://www.coursera.org/specializations/python-3-programming) on Coursera provided by University of Michigan


## What does this project do? ##
- Takes a ZIP file of images, extracts the images to a new folder.
- The images contained in the ZIP file are of newspaper pages. Every page contains text, and many of the pages contain images with faces in them.
- Takes any word as input (here we used 'Mark'), and searches each page for occurrences of the word with optical character recognition (OCR).
- If the word we searched for is found on the current page, then the program searches that page for pictures with faces in them. It then returns a contact sheet of thumbnail images with each face contained in the page where the word was found.
- Eg. if you search for 'Bill' it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "Bill".

Note: Due to the size of the images files used, they were stored in the .gitignore file in order to upload the project to GitHub. Original project materials can be found [here](https://www.coursera.org/learn/python-project).

---
# Original Project Description: #
### Python-Project-pillow-tesseract-and-opencv
[Course 5 of 5](https://www.coursera.org/learn/python-project) in the [Python 3 Programming Specialization](https://www.coursera.org/specializations/python-3-programming) on Coursera provided by University of Michigan

### About this Course

This course will walk you through a hands-on project suitable for a portfolio. You will be introduced to third-party APIs and will be shown how to manipulate images using the Python imaging library (pillow), how to apply optical character recognition to images to recognize text (tesseract and py-tesseract), and how to identify faces in images using the popular opencv library. By the end of the course you will have worked with three different libraries available for Python 3 to create a real-world data-analysis project.

The course is best-suited for learners who have taken the first four courses of the Python 3 Programming Specialization. Learners who already have Python programming skills but want to practice with a hands-on, real-world data-analysis project can also benefit from this course.

This is the fifth and final course in the Python 3 Programming Specialization.


### Learning Outcomes:

* How to inspect and understand APIs and third party libraries to be used with Python 3

* How to apply the Python imaging library ([pillow](https://github.com/python-pillow/Pillow)) to open, view, and manipulate images, including cropping, resizing, recoloring, and overlaying text

* How to apply the python tesseract ([py-tesseract](https://github.com/madmaze/pytesseract)) library with Python 3 in order to detect text in images through optical character recognition (OCR)

* How to apply the open source computer vision library ([opencv](https://github.com/opencv/opencv)) to detect faces in images, & how to crop and manipulate these faces into contact sheets