# MOWO: Mouse Only Walk Oooh

Tracks a mouse's paws on a DigiGait treadmill with a fine-tuned YOLOv3 detector, then turns the detections into per-paw step and position analytics.

## What's inside

- `notebooks/MOWO.ipynb` trains the detector
- `notebooks/localize-paw-inference.ipynb` runs inference and analytics
- `scripts/` holds the YOLO model and helpers

## How to run

```bash
pip install "tensorflow<2.12" "keras<2.12" "numpy<2"
pip install -r requirements.txt
jupyter notebook notebooks/MOWO.ipynb
```

Use Python 3.10 or older.

The training data and weights are on Kaggle; `input/readme.md` lists them.
