# HPC in Image Processing
Lecture presentation by 

## Why large images?
High quality high volume images 

FFTs (Fast Fourier Transforms) are the currency

Computer components have too little data transmission speeds: CPU, GPU, RAM, SSD, HDD

🏎️ Supercomputers compute a 6k x 6k x 6k 3D image in 30 seconds vs 2 days on a laptop

They are not built like a workstation, but like a data center:
- Relax irrigularities
- High speed interconnects
- High speed storage
- Balanced compute power

Terrabytes vs Petaflops:
A flop is a floating point operation, a terrabyte is a unit of data storage
- 1TB = 10^12 bytes
- 1PF = 10^15 flops

## Image processing in healthcare
The image created can be very detailed and large, up to 95% of the granularity. This allows for:
- MRI, CT, X-ray
- 3D reconstruction and simulation
    - Vascular flow in the brain
    - Blood flow in the heart
    - Measuring pressure of the ventricles
- Computational orthopedics
    - Take existing models and simulate impact points of the bone tissue

Kidney stones can be recognized by their shape and density
Wavelights for image segmentation
