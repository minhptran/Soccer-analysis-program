# Soccer-analysis-program
A program that uses AI/ML to analyze a soccer game live
The program detects and tracks players, referees and the ball in a video using YOLO. It also assigns players to teams based on the color of 
their uniform using Kmeans for pixel segmentation and clustering. This can also measure a team's ball acquisition percentage. Optical flow is used
to measure camera movement between frames, enabling accurate measuring of a player's movement, including their speed and distance covered.
![image](https://github.com/user-attachments/assets/36e2fdce-7850-4274-89a3-9c2a083774fe)

Modules Used 
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

**Trained Models**
- https://drive.google.com/file/d/1DFZu3whaQYICvV2pv8vY2U-ClvnKjGDU/view?usp=drive_link

**Input Video**
- https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view

To run this project, you need to have the following installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas
