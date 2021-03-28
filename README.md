# Real-time-face-mask-detection

## Setting up Face Mask Detection project in Ubuntu  

1. Clone the repo
```
> git clone https://github.com/Nannigalaxy/Real-time-face-mask-detection.git
```

2. Change your directory to the cloned repo and create a Python virtual environment named 'env', type the following commmand in command prompt
```
> virtualenv env -p python3
```

3. Activate the Virtual environment with
```
> source .\env\bin\activate
```

4. Now, run the following command in your Command Prompt to install the libraries required
```
> cd Real-time-face-mask-detection 
> pip3 install -r requirements.txt
```

## Setting up Face Mask Detection project in Windows  

1. Clone the repo
```
> git clone https://github.com/Nannigalaxy/Real-time-face-mask-detection.git
```

2. Change your directory to the cloned repo and create a Python virtual environment named 'env', type the following commmand in command prompt
```
> py -m venv env
```

3. Activate the Virtual environment with
```
> .\env\Scripts\activate
```

4. Now, run the following command in your Command Prompt to install the libraries required
```
> cd Real-time-face-mask-detection 
> pip3 install -r requirements.txt
```

## Run the project


3. To detect face masks in real-time video streams type the following command:
```
> python3 detect_mask_camera.py 
```
