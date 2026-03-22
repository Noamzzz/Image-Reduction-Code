# Astronomical Data Reduction Pipeline

This project implements a CCD data reduction pipeline in Python using FITS images.

## Overview

The goal is to calibrate raw astronomical images by removing instrumental effects and obtaining scientifically usable data.

The pipeline includes:
- Bias correction
- Dark current correction
- Flat-field correction
- Construction of master calibration frames
- Calibration of light images



The dataset includes observations of:
- **NGC 3532** (open cluster)
- **NGC 1976** (Orion Nebula)

## Requirements

- Python 3.x
- numpy
- matplotlib
- astropy

## Author

Noam Jansson
