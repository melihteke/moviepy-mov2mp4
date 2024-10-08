# MOV to MP4 Converter
A simple Python script to convert .mov files to .mp4 format using the moviepy library. The script ensures efficient video encoding with audio support by leveraging ffmpeg.

I do screen recording on my MacBook, which records videos in MOV format. These files take up a lot of space. Therefore, I created this script with the help of GitHub Copilot. Now, I can easily convert my MOV files to MP4 without using any third-party apps or websites.



## Installation
### Prerequisites
ffmpeg: Required for video processing.
moviepy: Python library for video editing.

### Install ffmpeg
On macOS, you can install ffmpeg using Homebrew:

```sh
brew install ffmpeg
```

### Install moviepy
You can install moviepy using pip:

```sh
git clone https://github.com/melihteke/moviepy-mov2mp4.git

cd moviepy-mov2mp4
```

```sh
pip install moviepy

or

pip install -r requirements.txt
```

### Example
Replace "test.mov" with the path to your .mov file.
Replace "output.mp4" with the desired output path for the .mp4 file.


### Run the script.

```sh
python main.py
```

