# CCFERD - Complex Context Facial Emotion Recognition Dataset

## Official paper:

Visual Prompting in LLMs for Enhancing Emotion Recognition

Vision Large Language Models (VLLMs) are transforming the intersection of computer vision and natural language processing; however, the potential of using visual prompts for emotion recognition in these models remains largely unexplored and untapped. Traditional methods in VLLMs struggle with spatial localization and often discard valuable global context. We propose a novel Set-of-Vision prompting (SoV) approach that enhances zero-shot emotion recognition by using spatial information, such as bounding boxes and facial landmarks, to mark targets precisely. SoV improves accuracy in face count and emotion categorization while preserving the enriched image context. Through comprehensive experimentation and analysis of recent commercial or open-source VLLMs, we evaluate the SoV model's ability to comprehend facial expressions in natural environments. Our findings demonstrate the effectiveness of integrating spatial visual prompts into VLLMs for improving emotion recognition performance.

![image_method](https://github.com/user-attachments/assets/828264d0-dacf-4471-9814-496c45328b31)

## Dataset Description
We collect original images from ABC News website {https://www.abc.net.au/news/}. Following the collection, we undertake meticulous preprocessing, initially removing any identical and blurry images through deduplication. To minimize human effort and cost in data annotation, we employ DeepFace for emotion annotation. Subsequently, two human annotators revise and refine the image labels. Finally, to finalize the labels, we involved a third annotator who has a professional background in psychology to verify correctness of facial expressions with their domain knowledge. This procedure guarantees the quality of the annotated data used to construct benchmarks.
The emotions are categorized into seven labels: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.

### Example Images
Some example images from the CCFERD dataset can be found in the datasets folder.

### Anonymity Requirements
To comply with anonymity requirements, the actual images from the dataset, along with the Python code and contact information, will be made publicly available once the paper is accepted.
