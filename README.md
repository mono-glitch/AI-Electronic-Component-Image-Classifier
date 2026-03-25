# **<ins>AI-Electronic-Component-Image-Classifier</ins>**

## Summary
- Designed CNN models (EfficientNetV2-S, ResNet50) & Vision Transformers to classify 32 electrical component classes, achieving >91% filtered accuracy and a 0.74 macro F1 score in final model ResNet50
- Addressed a 6.5× class imbalance by reweighing, and implemented image augmentation (cropping, rotation, brightness shifts), improving minority‑class recall and ensuring fairer performance for real‑world deployment

## Main Files

- **[project_IT1244.ipynb](https://github.com/mono-glitch/AI-Electronic-Component-Image-Classifier/blob/1214fa1ec292b5818735e0b19752645aafbcc3eb/project_IT1244.ipynb)** – The main notebook containing the methodology for dataset preprocessing, deep learning model development, and performance analysis.

- **[Project Report.pdf](https://github.com/mono-glitch/AI-Electronic-Component-Image-Classifier/blob/1214fa1ec292b5818735e0b19752645aafbcc3eb/Project%20Report.pdf)** – A comprehensive project report following AAAI format, detailing the rationale, methodology, results, and references.

- **[Models](https://drive.google.com/drive/folders/1o-S5imWw0PS8k0r-eAKh89uPM3fKqgr6)**
  
| Model File | Description |
|------------|-------------|
| EfficientNetV2S_model.keras | EfficientNetV2S architecture, optimized for balanced accuracy and efficiency with progressive learning and improved scaling. |
| ResNet50_model.keras | Base ResNet50 model, a 50-layer deep residual network known for effective feature extraction and reduced vanishing gradient. |
| FinalModel_ResNet50.keras | Final tuned ResNet50 model. |
| ViT1.keras | Vision Transformer (ViT) built from scratch, guided by the [official Keras documentation](https://keras.io/examples/vision/image_classification_with_vision_transformer/) on image classification with ViTs. |
| vit2.pth | Pre-trained vit_b_16 model from HuggingFace, implemented with reference to a [GitHub repository demonstration](https://github.com/GutlapalliNikhil/ImageClassification_VIT_TransferLearning/tree/main) on transfer learning with a ViT model pre-trained on ImageNet and applied to a custom dataset. |

## Other Files

- - **[project_IT1244.html](https://github.com/mono-glitch/AI-Electronic-Component-Image-Classifier/blob/1214fa1ec292b5818735e0b19752645aafbcc3eb/project_IT1244.html)** – A web-friendly version of the notebook for convenient viewing of the project outputs.

- **[Readme.pdf](https://github.com/mono-glitch/AI-Electronic-Component-Image-Classifier/blob/1214fa1ec292b5818735e0b19752645aafbcc3eb/Readme.pdf)** – Instructions for setting up the Python environment and running `project_IT1244.ipynb` from scratch.

- **[requirements.txt](https://github.com/mono-glitch/AI-Electronic-Component-Image-Classifier/blob/1214fa1ec292b5818735e0b19752645aafbcc3eb/requirements.txt)** – A list of Python libraries required to execute `project_IT1244.ipynb`.
