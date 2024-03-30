# Tennis Analysis 🎾

## Introduction 🌟
Tennis Analysis is a comprehensive tool designed for tennis enthusiasts, analysts, and players who wish to gain knowledge of the statistics 📊 and trends of the tennis world. Leveraging advanced data analysis techniques 📈 and visualization tools, this project aims to uncover insights from historical and current tennis matches, offering a unique perspective on player performances, match outcomes, and statistical trends.

## Features 🚀
- **Comprehensive Data Analysis:** Analyze data from various tennis tournaments, including Grand Slams, ATP, and WTA events. 📚
- **Interactive Visualizations:** Utilize interactive charts and graphs to explore tennis statistics and trends visually. 📉
- **Player Insights:** Gain insights into player performances, head-to-head records, and career progressions. 👟

## Models Used 🧠
To achieve our goals, we've employed the latest models:

Player Detection: YOLO v8
Tennis Ball Detection: Fine-Tuned YOLO ([Dataset](https://universe.roboflow.com/viren-dhanwani/tennis-ball-detection))
Court Keypoint Extraction: Customized CNNs

## Training Modules 📝

- [Tennis Ball Detector](training\tennis_ball_detector_training.ipynb): Training with YOLO
- [Tennis Court Keypoints](training\tennis_court_keypoints_training.ipynb): Training with PyTorch

## Getting Started 🏁

### Prerequisites 📋
To run Tennis Analysis, you'll need:
- Python 3.8 or higher 🐍
- Jupyter Notebook or JupyterLab 📓

### Installation 💾

1. Clone the repository to your local machine:

```bash
git clone https://github.com/VirajBhagiya/Tennis-Analysis.git
cd Tennis-Analysis
```
2. Install the required Python packages:

```bash
pip install -r requirements.txt
```
### Contributing 🤝
Contributions to the Tennis Analysis project are welcome! Whether it's fixing bugs 🐛, adding new features ✨, or improving the documentation 📝, please feel free to fork the repository and submit a pull request with your changes.

### Acknowledgments 👏
This project was inspired by and learned from [tennis analysis project](https://github.com/abdullahtarek/tennis_analysis). A huge thank you for laying the groundwork and inspiring further exploration in the realm of tennis.

