[//]: # (Image References)
[image_overview]: ./misc/weka_overview_cropped.png
[image_results]: ./misc/weka_results.PNG

# Weka document classification
![process overview][image_overview] 
Convert `.txt` files into weka accepted `.arff` files then classify the documents into four categories.

## Results
![classification results comparison][image_results] 

## Dataset Information
The data set includes 2803 training and 1396 test text based and composed of webpages collected from the computer science departments of various universities and are classified into four categories (student, faculty, project, and course).  The data set has already been preprocessed -- stop words removed and stemming performed.

## Strategy
Project information as well as a guided walk through can be found in `./report.pdf`.

## Use
- The python conversion is hard coded to read specific files in `./input/`, convert them, then write the output to `./output/`.
- To use WEKA, please download weka from [here](http://www.cs.waikato.ac.nz/ml/weka/).  Then follow the highlighted instructions included in `./report.pdf`

### Note:
The conversion input expects a specified input.  This could be easily modified in `./convert_txt_to_arff_specific.py`.  Notes about this input format are included in the `report.pdf`