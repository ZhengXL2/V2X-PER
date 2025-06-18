# V2X-PER
V2X-PER: A Pose-Robust One-Stage BEV Fusion Framework for Multi-Agent Collaborative Perception

This repository provides the official implementation of our one-stage collaborative perception framework for multi-agent autonomous driving scenarios. It features end-to-end sensor fusion, robust spatial alignment, and enhanced perception under pose perturbations.

---

## 📌 Open Source Roadmap

We plan to open-source the project in several phases to ensure code quality, documentation completeness, and reproducibility.

| Phase | Content                                                                 | Status     |
|-------|-------------------------------------------------------------------------|------------|
| 1️⃣   | Release model architecture and core modules (e.g., NSFM, PRAF, etc.)     | ⬜ Completed |
| 2️⃣   | Provide training & evaluation scripts, pretrained models                 | 🔄 In Progress |
| 3️⃣   | Release dataset preprocessing tools and visualization utilities         | ⬜ Pending |
| 4️⃣   | Publish benchmark results & detailed documentation                       | ⬜ Pending |

Stay tuned! We are actively maintaining and improving the codebase.

---

## 🚀 Installation

### Requirements

- Python >= 3.8  
- PyTorch >= 1.10  
- CUDA >= 11.1  
- GCC >= 7.3  
- Ubuntu 18.04 or higher  
- (Optional) ROS / Apollo for simulation integration

### Setup

```bash
# Clone the repository
git clone https://github.com/your_username/your_project_name.git
cd your_project_name

# (Optional) Create and activate a virtual environment
conda create -n collab-perception python=3.9
conda activate collab-perception

# Install dependencies
pip install -r requirements.txt

# Compile CUDA extensions (if any)
cd ops
python setup.py install
