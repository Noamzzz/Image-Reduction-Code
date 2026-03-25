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

![image alt](https://github.com/Noamzzz/Image-Reduction-Code/blob/d096739fbcd15374912adba057c7bc7814c24a2a/Workflow.png)

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

## References

- Amigo, P., & Toloza, O. (2026). *Actividad de clases 1: manejo de FITS en Python con Astropy*.  
- [Astropy FITS Image Handling](https://docs.astropy.org/en/latest/io/fits/usage/image.html#scaled-data)  
- [Astropy FITS Images Tutorial](https://learn.astropy.org/tutorials/FITS-images.html)  
- [Matplotlib imshow Documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.imshow.html)  
- [Astropy Documentation](https://docs.astropy.org/en/latest/)  
