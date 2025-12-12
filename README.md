# CS6886-Sys_for_dl-Assignment3
MobileNetV2 Quantization Assignment

# 📦 MobileNet-v2 Quantization Assignment  

---

## 📚 Background  
This repository contains the basic code to perform **Quantization** on the **VGG16** architecture trained on the **CIFAR-10** dataset.  
You can change the **quantization bits** of both the **weights** and **activations**, and evaluate model performance **before** and **after** quantization.  

---

## How to reproduce ?
we can run kaggle notebook which is mentioned below, the notebook contains data for all the stages mentioned info file.

In order to save time skip "Performing Training" cell as we have the best model already in the inputs of the notebook.

If you are running this notebook else where other than kaggle change this path in file

MODEL_SAVE_PATH = '/kaggle/input/best-model/best_mobilenetv2_CIPHAR10.pth'
