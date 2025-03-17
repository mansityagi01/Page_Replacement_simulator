📟 Page Replacement Algorithm Simulator

Python

This Python-powered tool uses Tkinter and Matplotlib to make operating system concepts pop. Simulate and compare FIFO, LRU, and Optimal algorithms with dazzling visualizations and real-time stats. 🚀
✨ Features

🧠 Algorithms: Explore FIFO, LRU, and Optimal page replacement strategies.

🖼️ Interactive GUI: Input page strings and frame sizes effortlessly with Tkinter.

📊 Visualizations:

Frame states and fault/hit timelines in real-time.

Side-by-side comparison of all algorithms with vibrant charts.

📈 Metrics: Instant page faults and hit ratios.

🛠️ Debug Mode: Optional logs for a peek behind the scenes.

📸 Screenshots

C:\Users\ASUS\OneDrive\Desktop\OS PROJECT\Screenshot 1.jpg

C:\Users\ASUS\OneDrive\Desktop\OS PROJECT\Scrrenshot 2.jpg

C:\Users\ASUS\OneDrive\Desktop\OS PROJECT\Screenshot 3.jpg

C:\Users\ASUS\OneDrive\Desktop\OS PROJECT\Screenshot 4.jpg

🌐 Flowcharts

C:\Users\ASUS\OneDrive\Desktop\OS PROJECT\Screenshot 5.jpg

🛠️ Prerequisites

🐍 Python 3.x

📦 Libraries:

tkinter (bundled with Python)

matplotlib

numpy

🚀 Installation

Clone the Repo:
bash git clone https://github.com/yourusername/page-replacement-simulator.git
cd page-replacement-simulator

Install Dependencies:
bash pip install matplotlib numpy

Launch the Simulator:
bash python page_replacement_simulator.py

🎮 How to Use

Start the App: Run the script to launch the GUI. 🔥

Enter Inputs:

Page String: Space-separated list (e.g., 7 0 1 2 0 3).

Frames: Number of frames (e.g., 3).

Algorithm: Choose FIFO, LRU, or Optimal. 🎯

Run It:

Simulate: Click to run one algorithm. 📉

Compare All: See all three in action with one click! ⚡

Reset: Clear everything to start over. 🧹

🗂️ Code Breakdown

page_replacement_simulator.py:

✨ init: Crafts the sleek GUI.

🚀 simulate: Powers a single algorithm run.

⚖️ compare_all: Battles all algorithms head-to-head.

🧩 fifo, lru, optimal: The algorithmic brains.

📊 plot_simulation: Creates the stunning visuals.

🌟 Example

Input:

Page String: 7 0 1 2 0 3 0 4 2 1 0 3

Frames: 3

Algorithm: FIFO

Output:

Step-by-step breakdown in the text box. 📜

Faults and hit ratio stats. 📊

Eye-catching plots of frame states and faults over time. 🎨

🙌 Acknowledgments

Built with ❤️ using Tkinter.

Visuals powered by Matplotlib.