# Real-time-face-mask-detection
This repo only provides inferencing of face mask detection for use in applications and serving. Original author for the code found in this repo is [Chandrika Deb](https://github.com/chandrikadeb7/Face-Mask-Detection).  
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Live Demo](https://github.com/Nannigalaxy/Real-time-face-mask-detection/blob/main/output/Demo.gif)

## Setting up Face Mask Detection project in Ubuntu  

1. Clone the repo
```
> git clone https://github.com/Nannigalaxy/Real-time-face-mask-detection.git
```

2. Change your directory to the cloned repo and create a Python virtual environment named 'env', type the following commmand in command prompt
```
> cd Real-time-face-mask-detection 
> virtualenv env -p python3
```

3. Activate the Virtual environment with
```
> source ./env/bin/activate
```

4. Now, run the following command in your Command Prompt to install the libraries required
```
> pip3 install -r requirements.txt
```

## Setting up Face Mask Detection project in Windows  

1. Clone the repo
```
> git clone https://github.com/Nannigalaxy/Real-time-face-mask-detection.git
```

2. Change your directory to the cloned repo and create a Python virtual environment named 'env', type the following commmand in command prompt
```
> cd Real-time-face-mask-detection 
> python3 -m venv env
```

3. Activate the Virtual environment with
```
> .\env\Scripts\activate
```

4. Now, run the following command in your Command Prompt to install the libraries required
```
> pip3 install -r requirements.txt
```

## Run the project


3. To detect face masks in real-time video streams type the following command:
```
> python detect_mask_camera.py 
```
## For Training and Results
https://github.com/chandrikadeb7/Face-Mask-Detection
