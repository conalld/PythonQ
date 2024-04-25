# PythonQ

Unofficial Python implementation of Metric Q proposed by Zhu and Milanfar - [https://ieeexplore.ieee.org/abstract/document/5484579]
Check MATLAB implementation for better understanding nuances - [https://github.com/radiobenzene/MetricQ]
# Usage
Check file [sampleUsage.py] for an example on how to measure Q

# Notes
- Q can only be run for images with H, W divisible by 8
- Q is only measured on Luma (Y) channel of the image

# Task List
- [X] Extract Luma Channel from image
- [ ] Add padding for images with non-divisible H, W
