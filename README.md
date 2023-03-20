
AI-powered voice assistant to assist the visually impaired in their daily tasks

AI Powered Vioice Assistant for Who are Blind or Have Low-Vision

be my eyes

power to the 253 million people who are blind or have low vision globally.
Image to text technology

The tool can offer suggestions for recipes based on the contents of a user's refrigerator, for example, and provide a step-by-step guide on how to make them.

Features:
Detecting 80 different categorical object types with their confidence level
Priority-based detection
Distance prediction & scaling algorithm
Mobile phone activated camera for various items
Speech-activated mode selection
Multi-threading usage for asynchronous voice warnings and feedbacks

Modes:
Aware mode: continuously speak out loud 3 items with the topmost priority
Warn mode: only shout out warnings if any item is too close based on priority
Search mode: focus on searching a particular item until it is found



### Features

- Detecting 80 different categorical object types with their confidence level
- Priority-based detection
- Distance prediction & scaling algorithm
- Mobile phone activated camera for various items
- Speech-activated mode selection
- Multi-threading usage for asynchronous voice warnings and feedbacks
- SSD Mobilenet COCO API Model

![cocoapimodel](https://i.stack.imgur.com/g30dc.png)

### Modes 

- Aware mode: continuously speak out loud 3 items with the topmost priority
- Warn mode: only shout out warnings if any item is too close based on priority
- Search mode: focus on searching a particular item until it is found

## Resources Links

Please click the link below to view our other resources regarding to this project submission.

1. [Submission Website](https://devpost.com/software/fix6dsense-ai)
2. [Demonstration Video](https://youtu.be/8zQXFG1x_Kw)
3. [Presentation Slides](https://www.canva.com/design/DAFN56ozY6E/K2jhOJD56fLkplBnkPWySg/view?utm_content=DAFN56ozY6E&utm_campaign=designshare&utm_medium=link&utm_source=publishpresent)

## How To Run

1. Clone this repository and make sure you have all the files downloaded

2. Set your environment and install the required python packages

    It is recommended for you to use Anaconda, and specifically `python version 3.9.0` (newer version of python has some compatibility issues related to the `collections` package, other older python version is untested and might have some compatibility issues as well). Then, install all the required python packages by typing:

    ```powershell
        pip install -r requirements.txt
    ```

3. Execute `main.py` or `main.ipynb` file

    If you want to use an external camera, you can connect via IP Webcam Pro and edit the `url` variable when running the model. By default, it is connected to your PC / Laptop default camera. You can also toggle the `USE_SPEECH` global variable to `True` or `False`. If it is `True`, it will use speech recognition to choose and change the mode, or else it will manually prompt you for the mode input.
