# Video Frame Extractor

Video Frame Extractor is a Flask web application that allows users to upload video files (including .mp4, .avi, .mov, .mkv, and .dat formats), extract frames at a specified frame rate, and view the extracted frames in a gallery.

## Features

- Upload video files (.mp4, .avi, .mov, .mkv, .dat)
- Extract frames from videos at a user-defined frame rate
- View extracted frames in a gallery
- Simple and user-friendly web interface

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/video-frame-extractor.git
    cd video-frame-extractor
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:
    ```bash
    python app.py
    ```

5. Open your web browser and navigate to `http://127.0.0.1:5000`.

## Usage

- Upload your video files using the upload form.
- Select the videos you want to process and specify the frame rate (fps).
- Click the process button to extract frames.
- View the extracted frames in the gallery section.

## File Structure
```bash
video-frame-extractor/
├── static/
│ └── uploads/ # Uploaded video files
├── templates/
│ ├── index.html # Main page
│ └── gallery.html # Gallery page for viewing extracted frames
├── output/ # Directory for storing extracted frames
├── app.py # Main application script
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```


## Requirements

- Python 3.x
- Flask
- OpenCV

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


