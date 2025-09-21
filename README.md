# DS (DifferentSports)-Estimation

This project demonstrates **pose estimation on athlete videos** using **OpenCV** and **MediaPipe** in Python. It tracks **joint angles** and generates **annotated videos** as well as **plots for movement analysis**.


## Features

-   Detects **human poses** in videos using MediaPipe.
-   Tracks **joint angles** (e.g., left elbow, right knee).
-   Annotates and saves processed videos (`*_pose.mp4`).
-   Plots **joint angles over time** for detailed analysis.
-   Supports **multiple athlete categories**: Basketball, Boxing, Football, Athletics, etc.

1.  **Create and activate a Python virtual environment** (Python 3.11 is recommended):
    ```bash
    conda create -n pose_env python=3.11
    conda activate pose_env
    ```

2.  **Install the required packages**:
    ```bash
    pip install opencv-python mediapipe matplotlib numpy
    ```

## How to Run

1.  Place your athlete videos inside the `Videos/` folder.
2.  Open `final.ipynb` in VSCode or Jupyter Notebook.
3.  Run the notebook cells in the following order:
    -   Imports & functions
    -   Define categories
    -   Analyze videos
    -   Plot joint angles
4.  Annotated videos will be saved automatically in the same folder with the `*_pose.mp4` suffix.

## Demo / Output Examples 

Here is an example of the output you can expect from the project.

### Annotated Video Output

<table align="center">
  <tr>
    <td align="center"><strong>Basketball Pose Estimation</strong></td>
    <td align="center"><strong>Boxing Pose Estimation</strong></td>
  </tr>
  <tr>
    <td>
      <img src="assets/basketball.png" alt="Annotated Basketball Pose Estimation" width="100%">
    </td>
    <td>
      <img src="assets/boxing.png" alt="Annotated Boxing Pose Estimation" width="100%">
    </td>
  </tr>
</table>

## Joint Angle Plots

<table align="center">
<tr>
<td align="center"><strong>Basketball Joint Angles</strong></td>
<td align="center"><strong>Football Joint Angles</strong></td>
</tr>
<tr>
<td>
<img src="assets/joinbask.png" alt="Plot of basketball joint angles" width="100%">
</td>
<td>
<img src="assets/joinfoot.png" alt="Plot of football joint angles" width="100%">
</td>
</tr>
</table>

## Application in Sports

1.  Helps player to analyse their shooting posture
2.  Helps coaches to replan the training sessions for players
3.  For identifying skills
4.  Injury prevention, Rehabilitation Support
