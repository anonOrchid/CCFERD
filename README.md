# CCFERD - Complex Context Facial Emotion Recognition Dataset

## Official implementation of our paper:
Visual Prompting in LLMs for Enhancing Emotion Recognition

Vision Large Language Models (VLLMs) are transforming the intersection of computer vision and natural language processing; however, the potential of using visual prompts for emotion recognition in these models remains largely unexplored and untapped. Traditional methods in VLLMs struggle with spatial localization and often discard valuable global context. We propose a novel Set-of-Vision prompting (SoV) approach that enhances zero-shot emotion recognition by using spatial information, such as bounding boxes and facial landmarks, to mark targets precisely. SoV improves accuracy in face count and emotion categorization while preserving the enriched image context. Through comprehensive experimentation and analysis of recent commercial or open-source VLLMs, we evaluate the SoV model's ability to comprehend facial expressions in natural environments. Our findings demonstrate the effectiveness of integrating spatial visual prompts into VLLMs for improving emotion recognition performance.

![图片 1](https://github.com/user-attachments/assets/828264d0-dacf-4471-9814-496c45328b31)

## Dataset Description
The CCFERD dataset consists of a wide range of facial images, each annotated with emotion labels. The images encompass various contexts, including multiple faces per image, different lighting conditions, and varied backgrounds, to simulate real-world conditions. This diversity is intended to enhance the robustness and generalization of emotion recognition models trained on this dataset.

### Example Images
Some example images from the CCFERD dataset can be found in the datasets folder.

### Anonymity Requirements
To comply with anonymity requirements, the actual images from the dataset, along with the Python code and contact information, will be made publicly available once the paper is accepted.
