# Thai OCR engine open-source initiative

This project aims to have an open-source Thai OCR engine for leveraging a digitization process in the organization. So in the first steps, I have finished some proof-of-concept project with concerning Thai royal gazette documents (เอกสารราชกิจจานุเบกษา.) Here is my work for doing an OCR process.

Note that the source code will not provided in this repository anyway since there is a glitch in the code of OCR. I will describe only related algorithms which contain as the following:

1. Straight line detection
2. Region of interest detection
3. Text recognition

## Overview
![[overview_ocr.png]]

## Straight line detection
![[straight_line_OCR.png]]

## Region of interest detection
![[ROI_OCR.png]]
### Why don't we use $x$-axis to cluster a bunch of characters?
![[Character_contour_OCR.png]]
Usually, Thai language has a linear writing system, $x$-axis can be neglected if we are interested in line detection.

## Text recognition
![[Tesseract_OCR.png]]

## Pain points
![[Pain_points.png]]