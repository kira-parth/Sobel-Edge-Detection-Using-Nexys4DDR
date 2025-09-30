# FPGA-Based Real-Time Sobel Edge Detection System
 Hardware-accelerated image processing system implementing Sobel edge detection on Xilinx Nexys4 DDR FPGA with Python GUI
# Results
<img width="1730" height="1027" alt="Screenshot 2025-09-29 012713" src="https://github.com/user-attachments/assets/273c61ac-cfda-4c23-99ea-244b3541544e" />

# Project Overview
This project demonstrates a complete hardware-software co-design implementing the Sobel edge detection algorithm on FPGA hardware. The system achieves 95,936 pixels/second processing speed by leveraging parallel computation capabilities of the Xilinx Artix-7 FPGA.

# Key Features
True Sobel Implementation: Proper 3×3 convolution with Gx and Gy gradient kernels
Hardware Acceleration: 42ms processing time for 256×256 images
Real-time Communication: UART interface at 115200 baud rate
Professional GUI: Modern Python interface with live visualization
Binary Edge Output: Thresholded edge map for clear edge detection
# System Architecture 
<img width="1352" height="712" alt="sobel_architecture" src="https://github.com/user-attachments/assets/0165f8b4-f33c-4269-ae86-65776bb5e8c6" />
