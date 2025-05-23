# 📌 YouTube Video to Notes

## 🎯 Overview
Convert YouTube videos into a summarized PDF with extracted key frames. This tool helps in quick note-taking and reference by automatically capturing distinct frames from a video.

## 🚀 Features
- Extracts unique frames based on structural similarity index (SSIM)
- Converts extracted frames into a PDF with timestamps
- Supports various YouTube URL formats
- Web-based interface using Flask
- Automatically downloads and processes videos

## 🔥 How It Works
1. Enter a YouTube video URL.
2. The tool downloads the video and extracts key frames.
3. The extracted frames are compiled into a PDF.
4. The PDF is available for download.

## 🎯 Problem It Solves
- Helps students and researchers quickly capture key moments from educational videos.
- Saves time by eliminating manual screenshotting.
- Provides an organized way to revisit important visuals from videos.

## ⚡ Challenges Faced
- **Frame redundancy**: Implemented SSIM to filter out similar frames.
- **Different YouTube URL formats**: Used regex to extract video IDs properly.
- **Efficient frame extraction**: Adjusted frame selection frequency to balance quality and file size.

## 🛠 Technologies Used
- **Python**
- **Flask**
- **OpenCV**
- **scikit-image (SSIM)**
- **yt-dlp**
- **FPDF**
- **PIL (Pillow)**
- **Regex**
- **HTML, CSS**

## 🏗 Installation & Usage
```bash
# Clone the repository
git clone https://github.com/avinashg0y4l/video2pdf.git
cd youtube-video-to-notes

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
```

## 💡 Future Enhancements
- Add **speech-to-text** for generating textual summaries.
- Provide **frame annotation** for additional insights.
- Support **customized frame extraction intervals**.

## 🤝 Contributing
Feel free to submit issues or pull requests to improve the project.

## 📜 License
This project is open-source and available under the MIT License.
