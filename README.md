# 3D-vs-Real-Object-Measurement

## Purpose

The purpose of this project is to verify whether a 3D-modeled object has been accurately formed after production, by comparing its physical dimensions with its digital STL model.

Using top and side view images of the real object, OpenCV is employed to measure key dimensions such as thickness, width, and height. These measurements are then compared to the corresponding values derived from the 3D model using Open3D.

This project showcases practical skills in computer vision, dimensional analysis, GUI design with PyQt5, and CAD model validation.

---

## Features

- Dimension extraction from 2D images using OpenCV
- Comparison of real vs. 3D model dimensions
- STL model visualization using Open3D
- User-friendly GUI interface (PyQt5)
- Works with different object types (e.g. Matchbox, RoundCap)

---

## Requirements

- Python 3.11+
- OpenCV
- Open3D
- PyQt5
- NumPy

## Install Dependencies

```bash
pip install -r requirements.txt

```

## Run
```bash
python main.py
```

## Contributors

| Name               | GitHub Profile                                  |
|--------------------|-------------------------------------------------|
| Muttalip Çiçek     | [@muttalip488](https://github.com/muttalip488) |
| Mehlika Ebru Aydın | [@mehlikaebruaydin](https://github.com/mehlikaebruaydin) |





