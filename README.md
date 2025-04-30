## Code set up and instructions 

The experimental framework of GATERN is implemented in Python 3.9.7 using Jupyter Notebooks for ease of modular experimentation and interpretability. To facilitate reproducibility and flexibility, the framework is structured to support both feature extraction and training using pre-extracted features.
## Feature Extraction
The feature extraction is performed in two different stages:
### audio feature extraction: 
can be extracted using teh EDA notebook file named crema-d-emotion-recognition_full_data.ipynb file provided, the metadata file can be generated using the same notebook file.
### video feature extraction
video features are extracted using the VGG-face model provided in UTERN repo, the 4096 dimensional feature vectors obtained are then reduced to a 50 dimensional vector.

Both the audio features and the video features are pre-extracted  for CREMA-D along with the metadata file and can be downloaded from: https://livewarwickac-my.sharepoint.com/:f:/g/personal/u2066241_live_warwick_ac_uk/ElM7BeLWXMNFlFwIDTswZlsBXueezqZmgD3w0WY1PpHhHA?e=t8G5nv
# Training and testing:
The model can be trained and tested using the GRUAttention.ipynb file 
