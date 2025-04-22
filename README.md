# Performance Analysis of Players in the Vietnam National Football Team's Match Using the YOLOv8 Model

This project focuses on applying computer vision techniques—specifically the YOLOv8 object detection model—to analyze the performance of players in matches played by the Vietnam National Football Team. It aims to track players, extract key metrics, and provide insights for post-match analysis.

## 📌 Project Objectives

- Detect and track football players in video footage using YOLOv8.
- Analyze players' movements, speed, and positions over time.
- Generate performance metrics that could assist coaches and analysts.
- Support Vietnamese football with AI-based video analysis tools.

## 🧠 Technologies Used

- **YOLOv8** (Ultralytics) – for object detection and tracking.
- **OpenCV** – for image processing and video handling.
- **Python** – as the core programming language.
- **Jupyter Notebook** – for prototyping and analysis.
- **Google Colab** – for cloud-based training and testing.

## 📂 Project Structure

```
📁 YOLOv8-Player-Analysis/
├── 📁 dataset/              # Sample training and evaluation videos/images
├── 📁 notebooks/           # Jupyter notebooks for training and evaluation
├── 📁 results/             # Output results and visualizations
├── 📄 requirements.txt     # List of required packages
└── 📄 main.py              # Script for running the complete pipeline
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/HungKai30/Performance-Analysis-of-Players-in-the-Vietnam-National-Football-Team-s-Match-Using-the-YOLOv8-Model.git
   cd YOLOv8-Player-Analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the main script:
   ```bash
   python main.py
   ```

4. (Optional) Run notebooks in `notebooks/` folder for step-by-step demonstration.

## 📈 Sample Results

- Player tracking overlayed on match video.
- Distance covered
- Speed and position tracking graphs.

## 📌 Future Improvements

- Integrate pose estimation for finer-grained performance metrics.
- Automate player identification and jersey number recognition.
- Build a dashboard to visualize metrics live during matches.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).