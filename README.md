
# Video Background Remover

This repository contains a Jupyter Notebook (**BG_Remover.ipynb**) that demonstrates how to remove the background from a video. The notebook processes an input video frame-by-frame, removes the background, and produces an output video with the background replaced.

## Features

- **Video Processing:** Reads an input video, processes each frame to remove the background, and writes an output video.
- **Easy Setup:** Automatically clones required repositories and downloads necessary files.
- **Visualization:** Displays a side-by-side comparison of the first frames from the input and output videos.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/RituRajKumarWork/Video-Background-Remover.git
   cd Video-Background-Remover
   ```

2. **Install Dependencies**

   Ensure you have Python 3.7 or later installed, then run:

   ```bash
   pip install torch torchvision opencv-python pillow matplotlib gdown
   ```

## Usage

1. **Open the Notebook**

   Launch Jupyter Notebook or Google Colab and open **BG_Remover.ipynb**.

2. **Configure Video Paths**

   Update the following variables in the notebook with your video file paths:

   ```python
   input_video_path = '/content/Test.mp4'      # Path to your input video
   output_video_path = '/content/output_bg_removed2.mp4'
   ```

3. **Run the Notebook**

   Execute the cells sequentially. The notebook will:
   - Set up the environment and download necessary resources.
   - Process the video frame-by-frame to remove the background.
   - Save the output video to the specified location.
  

##Output
![image](https://github.com/user-attachments/assets/e792b77c-57e7-4f9a-9d79-84910c9d5d07)


## Notes

- **Performance:** Processing time will vary depending on the input video's length and your system's performance.
- **Warnings:** You may see some warnings related to PyTorch; these do not affect the functionality.
- **Customization:** The project focuses on core functionality. You can extend or modify the code to better suit your needs.

## License

This project is provided for educational purposes. Please refer to the repository’s license file for more details.
