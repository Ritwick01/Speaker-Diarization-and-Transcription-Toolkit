# Speaker Diarization and Transcription Toolkit

Speaker Diarization and Transcription Toolkit is a Streamlit-based application that enables users to perform speaker diarization, divide audio and video into different speaker segments, listen to individual speakers, and generate speaker transcriptions using the Pyannote.audio and Whisper models.

## Getting Started

To get started with the project, follow these steps:

### Prerequisites

Make sure you have Anaconda installed on your system.

### Installation

1. Clone this repository to your local machine:
    git clone <https://github.com/Dheeraj9811/Speaker-Diarization-and-Transcription-Toolkit>

2. Navigate to the project directory:

3. Create a Conda environment using the provided environment files:
conda env create -f req_model_2.txt -f environment.txt

4. Activate the Conda environment:
conda activate <environment_name>

### Running the Application

To run the application, execute the following command:
--- streamlit run app.py


## Usage

Once the application is running, open your web browser and navigate to the URL provided by Streamlit (usually `localhost:8501`). You will see the Speaker Diarization and Transcription Toolkit interface, where you can upload audio or video files, perform speaker diarization, listen to individual speakers, and generate speaker transcriptions.

## Contributing

Contributions are welcome! If you have any ideas for improvements, features you'd like to see, or bug fixes, feel free to open an issue or submit a pull request.

## License



## Acknowledgments

- Pyannote.audio: A toolkit for speaker diarization.
- Whisper models: State-of-the-art models for speaker diarization and transcription.

