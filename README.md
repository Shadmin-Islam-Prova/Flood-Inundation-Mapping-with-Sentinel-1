# Flood-Inundation-Mapping-with-Sentinel-1
A satellite remote sensing project implementing automated flood detection and multi-temporal monitoring in Bangladesh's North Eastern Flood Prone district, Sylhet flood 2022 using Synthetic Aperture Radar (SAR) imagery. This repository builds upon the methodology presented in the Copernicus RUS Training series videos in youtube. 

## Project Overview

Sudden flash flood on mid 2022 in Sylhet district resulted in severe humanitarian and environmental impacts. Cloud cover during intense rain events often prevents optical satellite imagery from observing the ground. Synthetic Aperture Radar (SAR) sensors—such as Sentinel-1 operate at microwave frequencies (C-band), penetrating clouds and operating day or night. Smooth water bodies act as specular reflectors, scattering radar signals away from the sensor and appearing dark in SAR imagery. This project extracts flood extent masks by thresholding preprocessed Sentinel-1 imagery across a multi-temporal baseline. The workflow also utilized satellite imagery to detect flooded areas through change detection and threshold-based water classification.
