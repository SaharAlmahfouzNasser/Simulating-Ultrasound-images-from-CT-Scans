# Simulating-Ultrasound-images-from-CT-Scans

This work got accepted at the Bioimaging Conference 2023
Currently the Arxiv version of this paper is available at:
https://www.medrxiv.org/content/10.1101/2023.01.16.23284615v1

# How to run the code:

1. Install Stride: follow the guidelines in https://github.com/trustimaging/stride
2. Create a folder which contains your CT images. You can download CT images from the following link: 
https://www.cancerimagingarchive.net/
3. Run the script "CT2SoS.ipynb" to convert the CT image into speed of sound image. The outputs of this script are two files the speed of sound image (Med.h5) and the blurred speed of sound image (Med_blur.h5)
4. Run the script "GPU_01_jupyter_forward-att.ipynb"
5. Run the script "GPU_02_jupyter_inverse-att.ipynb"
And we are done :)

Note:
As we designed our transducer you should add the functions mentioned in "Extra_Functions.txt" to the corresponding scripts in Stride. Or dirctly use the modified scripts "geometries.py", and "geometry.py"
 




# If you find our work useful, kindly cite our paper:

@article{almahfouz2023simulating,
  title={Simulating Ultrasound images from CT Scans},
  author={Almahfouz Nasser, Sahar and Sethi, Amit},
  journal={medRxiv},
  pages={2023--01},
  year={2023},
  publisher={Cold Spring Harbor Laboratory Press}
}
