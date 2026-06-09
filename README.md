# Storage-Comparison
Storage Comparisons

I'll create SVG architecture/block diagrams for each storage type, then a comprehensive comparison table as an HTML file. 

Here's the 5 files:

Diagrams (SVG images) — each shows both a physical architecture view and a block diagram side by side:
hdd_diagram.svg — platters, R/W heads, actuator arm, spindle motor, controller PCB
optical_diagram.svg — disc structure, laser pickup (OPU), photodetector, servo block diagram
ssd_diagram.svg — M.2 PCB with NAND dies, controller SoC, DRAM cache, SATA connector
nvme_diagram.svg — M.2 PCB, 3D NAND stacks, multi-core NVMe controller, PCIe lanes

Comparison Table (HTML) — storage_comparison.html covers:
Category --- What's compared
Storage Medium --- Physical encoding, moving parts, form factors
Interface & Protocol --- SATA vs PCIe, queue depths, bus bandwidth
Performance --- Sequential R/W, random 4K IOPS, access latency with visual bars
Capacity & Cost --- Typical ranges, $/GB estimates
Architecture --- Data organization, controllers, cache, ECC methods
Reliability --- Shock resistance, write endurance, MTBF, data retention
Power & Thermal --- Idle/active wattage, noise
Use Cases --- Ideal workloads, OS support, encryption
Star Ratings --- Quick-glance performance tier summary
