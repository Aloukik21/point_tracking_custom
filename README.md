# User defined point tracking and saving coordinates to csv file
# Lucas–Kanade method

It assumes that the flow is essentially constant in a local neighbourhood of the pixel under consideration, and solves the basic optical flow equations for all the pixels in that neighbourhood, by the least squares criterion.

By combining information from several nearby pixels, the Lucas–Kanade method can often resolve the inherent ambiguity of the optical flow equation. It is also less sensitive to image noise than point-wise methods. On the other hand, since it is a purely local method, it cannot provide flow information in the interior of uniform regions of the image.


# **Softwares required**

1. Anaconda 3 (optional)
2. Python=3.6


# **Python Libraries required**

Please check requirement.txt file (all the libraries will be installed automatically)


# **Installation steps**

1. Open CMD in translation folder
2. Command 1: conda create -n points python=3.6
3. Command 2: conda activate points
4. Command 3: pip install -r requirements.txt  
5. Command 4: jupyter notebook –generate-config
6. Command 5: jupyter notebook
7. Jupyter notebook will open in the browser.
8. Click on translation.ipynb file
9. Run all the cells using shift+enter keys
10.While running the the main code cell, new window will pop up with an image
11.Select four or user defined points on the image and hit enter
12.Continue running all the cells.
13.Csv files will be saved in the current directory
14.For precise steps, please follow the tutorial_video


# DEMO

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/30460954/144480184-1173c456-ec90-41d9-b46f-75cbc8859c97.gif)

# **Author**
Name: Aloukik Aditya (Computer Vision Engineer / Machine learning engineer)

Email: aloukikaditya@gmail.com
