# LightCNNRad-DepthNet

## About the Project

In this project, we introduce two CNN architectures, **LightCNNRad** and **DepthNet**, designed to optimize computational efficiency while maintaining high performance. These novel architectures are tailored specifically for radiological image analysis. Key highlights include:

- **Performance:** Comparable performance to the more complex pre-trained VGG-16 models.
- **Efficiency:** Significant reductions in computational complexity.
- **Versatility:** Successfully applied across various imaging modalities, including MRI, CT, X-ray, and Ultrasound.

Our findings demonstrate that simpler architectures can achieve competitive performance, highlighting the potential of **LightCnnRad** and **DepthNet** in clinical settings where computational resources and real-time processing are critical. This study addresses the limitations of traditional deep learning models, such as VGG-16, by proposing simplified architectures that maintain high performance while reducing computational demands.

## Usage

**LightCNNRad** and **DepthNet** can be employed in clinical settings to analyze a wide range of medical images, from MRI to Ultrasound. These algorithms are implemented using the PyTorch framework. To use these models, please ensure that you have:

1. Installed the PyTorch framework.
2. Installed other required Python libraries.

## Installation

Pytorch framework is used for the implementation of LightCNNRad and DepthNet. To install PyTorch and TorchVision (with CUDA v. 12.1), you can either visit the [Pytorch website](https://pytorch.org/get-started/locally/) to install it on a specific OS or run the following command in the Windows command prompt:

```bash
# Installing Pytorch
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```
In order to install the required packages, you will first need to install and upgrade 'pip' via this command:

```bash
python -m pip install --upgrade pip
```

Execute the following command to install the required packages:

```bash
pip install -r required_packages.txt
```
***Note***: please ensure that you have downloaded the "required_packages.txt" before running the above command.  

## Contribution

This project was supervised by [**Dr. Pegah Khosravi**](https://scholar.google.com/citations?hl=en&user=lHM6ZCwAAAAJ) at the  [**BioMind AI lab**](https://sites.google.com/view/biomind-ai-lab). The following authors have contributed to this project:

- Saber Mohammadi
- Abhinita S. Mohanty
- Shady Saikali
- Doori Rose
- WintPyae LynnHtaik
- Raecine Greaves
- Tassadit Lounes
- Eshaan Haque
- Aashi Hirani
- Javad Zahiri
- Iman Dehzangi
- Vipul Patel
- Pegah Khosravi

## 📚 How to Cite

When referencing this repository, please use the following citation format:

**S. Mohammadi et al., "Beyond Algorithms: The Impact of Simplified CNN Models and Multifactorial Influences on Radiological Image Analysis," MedRxiv, 2024, doi: https://doi.org/10.1101/2024.09.15.24313585, **

![image](https://github.com/user-attachments/assets/276c5d62-7bfe-46fa-9cf3-6559e57e75ca)

