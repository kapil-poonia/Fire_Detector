# Fire Detection Alarm System
This system can detect fires on video frames. I have used HSV algorithm to track fires in images and video. 

## This system has three main features-
1. Detect fire in video frame.
2. Turn on alarm sound .
3. Send emails to fire engine services.

# Create .env file
```
  EMAIL=<Your Email Address>
  PASSWORD=<Your Password>
```

# Initial setup

## Create Virtual environment
```
  python -m venv ./env
```

## Activate Virtual environment (for windows)
```
  ./env/Scripts/activate
```

## Install requirements
```
  pip install -r requirements.txt
```

# System Requirments
- Laptop With Internet
- Python 3.7 or later versions
- Python Libraries
  - cv2 - Command(pip install opencv-python)
  - numpy - Command(pip install numpy)
  - smtplib - Command(pip install secure-smtplib)
  - playsound - Command(pip install playsound)

# How To Use
- Download an image which you want to work on in .mov format.
- Open the command prompt and run the python file.
``` 
  python ./fire_detector.py
```



