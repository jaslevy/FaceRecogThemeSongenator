# Pi Face Jukebox

Welcome to the Pi Face Jukebox! This project allows you to create a fun and interactive experience by playing unique theme songs for people who enter a room based on facial recognition. The system utilizes a computer running MacOS and the OpenCV library to achieve this functionality (for the Raspberry Pi alternative, click [here](https://github.com/krisselberg/PiFaceJukebox)).

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Quickstart](#quickstart)

## Introduction

This project aims to create a personalized and entertaining environment by associating theme songs with individuals through facial recognition. When someone enters a room monitored by the Raspberry Pi camera, the system will identify their face and play a predefined theme song associated with that person.

**Key features of the Facial Recognition Theme Song Generator:**

- **Facial Recognition:** The system uses OpenCV + an SVM to perform facial recognition.

- **Personalized Theme Songs:** You can configure the system to play unique theme songs for different people.

- **Raspberry Pi Integration:** The project is designed to run on a Raspberry Pi.

## Requirements

Before getting started, ensure you have the following hardware and software requirements:

### Hardware

- macOS Computer

<<<<<<< HEAD

### Software

- Raspbian OS (or any Raspberry Pi compatible Linux distribution)
- Python 3.x
- OpenCV library
- Pydub

## Installation

=======

## Quickstart

> > > > > > > dfde960 (updated readme)

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/jaslevy/PiFaceJukebox
   ```

2. **Install Dependencies:**
   <<<<<<< HEAD

Navigate to the project directory and install the required Python packages:

````bash
cd facial-recognition-theme-song
pip install -r requirements.txt

=======
Navigate to the project directory and install the required Python packages:

```bash
cd PiFaceJukebox
pip install -r requirements.txt
````

3. **Prepare the Music Directory:**
   Create a directory named music in the project folder and place the theme song files (.mp3 or .m4a formats) in this directory. Each file should be named after the person it is associated with.

4. **Collect Training Data:**
   Capture images of the people you want to recognize and assign theme songs to. Use the face_script script included in the project:

```bash
python face_script.py
```

Enter the name of the person when prompted (should be the same as their associated music file), and capture several images of their face in different angles and lighting conditions.

5. **Train the Facial Recognition Model:**
   Once you have collected enough images, run the training script to generate the face recognition model:

```bash
python train.py
```

6. **Run the Pi Face Jukebox**
   Start the facial recognition theme song player:

```bash
python main.py
```

## Troubleshooting

If you encounter issues, here are some common troubleshooting steps:

- Ensure all hardware components are correctly connected and configured.
- Check if the audio output is configured correctly on your Raspberry Pi.
- Ensure all dependencies are correctly installed and compatible with your Raspberry Pi.
  > > > > > > > dfde960 (updated readme)
