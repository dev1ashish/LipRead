# LipReading: End-to-End Sentence-level Lipreading using Deep Learning 🎥🔊

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/) [![AI/ML](https://img.shields.io/badge/AI/ML-FF6F00?style=for-the-badge&logo=artificialintelligence&logoColor=white)](https://en.wikipedia.org/wiki/Machine_learning) [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/) [![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)

This project is a low-level implementation of the paper titled "**LipNet: End-to-End Sentence-level Lipreading**" ([link](https://arxiv.org/abs/1611.01599)), which uses deep learning techniques for recognizing lip movements and converting them into text. Unlike the original paper, this implementation employs static slicing instead of the deep learning approach described in the paper.

The model utilizes the GRID corpus database ([link](http://spandh.dcs.shef.ac.uk/gridcorpus/)) for training and evaluation purposes. The dataset and pre-trained model links are provided in the accompanying Jupyter Notebook.

This project features a full-stack web application built using Streamlit, allowing users to interact with the lipreading model through a user-friendly interface.

## Features

- Low-level implementation of the LipNet paper using static slicing
- Utilizes the GRID corpus database for training and evaluation
- Full-stack web application built with Streamlit for easy interaction
- Jupyter Notebook with links to dataset and pre-trained model downloads

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/dev1ashish/LipRead.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Launch the Streamlit web application: `streamlit run app.py`

## Real-Life Applications

- **Accessibility for the Hearing Impaired**: Facilitate communication and improve quality of life for individuals with hearing difficulties by providing real-time captioning through lip movement recognition.

- **Speech Recognition in Noisy Environments**: Complement traditional speech recognition systems in environments with high ambient noise, where audio input may be unreliable.

- **Human-Computer Interaction**: Enable hands-free input by allowing users to issue commands or input text through lip movements, beneficial in scenarios where physical input devices or voice commands are impractical.

- **Multimedia and Entertainment**: Enhance animated films, video games, and video captioning by providing accurate lip-syncing and subtitles through lip movement analysis.

- **Surveillance and Security**: Aid in identifying individuals or extracting relevant information from video footage by interpreting lip movements, even when audio is unavailable or unreliable.
  
## Acknowledgments

- The authors of the "LipNet: End-to-End Sentence-level Lipreading" paper for their groundbreaking work.
- The creators of the GRID corpus database for providing the dataset used in this project.
- The Streamlit team for their excellent web application framework.
