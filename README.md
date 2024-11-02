# Temporal Multimodal Sequences for Audio-Video-Language Modelling

## Project Description

This project aims to learn musical representations for answering questions about music performances. It involves processing audio files, performing pre-processing, and running various machine learning models to extract meaningful features and answer performance-related questions.

## Installation Instructions

1. Clone the repository:
    ```sh
    git clone it
    cd amuse
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage Instructions

To run the project, execute the following scripts in the specified order:

1. **Extract audio features:**
    ```sh
    python extract_audios.py
    ```

2. **Pre-process RTVA and STVA data:**
    ```sh
    python rtva_stva_pre.py
    ```

3. **Pre-process YOLO data:**
    ```sh
    python yolo_pre.py
    ```

4. **Run the main training script:**
    ```sh
    python main_training.py
    ```

## Configuration

All configurations are located in the `config` files. You can modify the parameters according to your requirements.

## Dataset and checkpoints

The dataset and checkpoints can be downloaded from the following links: [https://www.dropbox.com/scl/fi/jj18w7rzu5kwh4do0r6hp/amuse_files.zip?rlkey=r2y6haw7twfjhqfphuyi12jts&st=8awhutek&dl=0](https://www.dropbox.com/scl/fi/jj18w7rzu5kwh4do0r6hp/amuse_files.zip?rlkey=r2y6haw7twfjhqfphuyi12jts&st=8awhutek&dl=0) 

