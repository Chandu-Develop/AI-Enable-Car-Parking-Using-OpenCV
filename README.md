# AI-Enable-Car-Parking-Using-OpenCV
Car parking is a common problem faced by drivers in busy urban areas. For example, imagine you are driving to a shopping mall during peak hours. As you approach the mall, you notice that the parking lot is full, and several other cars are circling around looking for available spots.

You join the queue of cars, hoping to find an available spot soon. However, as time passes, you realize that the parking lot is overcrowded, and it's becoming increasingly difficult to find a spot. You start to feel frustrated and anxious, knowing that you might be late for your appointment or miss out on a great shopping opportunity.

AI-enabled car parking using OpenCV is a computer vision-based project that aims to automate the parking process. The project involves developing an intelligent system that can identify empty parking spaces and gives the count of available parking spots.

The system uses a camera and OpenCV (Open Source Computer Vision) library to capture live video footage of the parking lot.

Pre-Requisites
    To complete this project you must have the following software versions and packages. 
    To make a responsive Python script you must require the following packages. 
    
    
    PyCharm ( Download: https://www.jetbrains.com/pycharm/ ) 
    
    Python 3.7.0 (Download: https://www.python.org/downloads/release/python-370/ )
    
    Numpy
    
    cvzone
    
    Flask: 
    
      - Web framework used for building web applications. 
        
      - Flask Basics: Click here 
    
    If you are using anaconda navigator, follow the below steps to download the required packages: 
    
      - Open anaconda prompt. 
        
      - Type "pip install opencv-python” and click enter. 
        
      - Type "pip install cvzone” and click enter. 
        
      - Type “pip install Flask” and click enter. 
    
    If you are using Pycharm IDE, you can install the packages through the command prompt and follow the same syntax as above.
    

Project Flow
    - Data Collection
    
        - Download the dataset
    
    - ROI (Region of interest)
    
      - Create Python file
      
      - Import required libraries
      
      - Define ROI width and height
      
      - Select and deselect ROI
      
      - Denote ROI with BBOX
    
    - Video Processing and object detection
    
        - Import required libraries
        
        - Reading input and loading the ROI file
        
        - Checking for parking space
        
        - Looping the video
        
        - Frame processing and empty parking slot counters
    
    - Cloud  Database Connection
    
        - Create a cloud  DB2 service and table
    
    - Application building
    
        - Build HTML
    
        - Build Python script for Flask
    
In this project, we created individual directories to store Python files that deal with backend and HTML, CSS files that manage the frontend part
In this project, we built an AI model 
