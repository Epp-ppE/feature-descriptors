## FAST / BRIEF / ORB experiments

- `experiments.ipynb` – a simple walkthrough of FAST, BRIEF and ORB in OpenCV, with demos of each one's strengths and issues
- `images/` – test images (`sceneN_angle1/2` show the same scene from two camera angles)

## Run

```
python -m venv .venv
.venv\Scripts\pip install -r requirements.txt   # needs opencv-contrib-python for BRIEF
.venv\Scripts\python -m ipykernel install --user --name feature-descriptors
```

Then open `experiments.ipynb`, select the **Python (feature-descriptors)** kernel and run all cells.

Do not install `opencv-python` together with `opencv-contrib-python`; they conflict.
