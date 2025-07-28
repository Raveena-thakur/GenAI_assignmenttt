--Model Structure
This project implements a sequence-to-sequence model using an encoder-decoder architecture built with LSTM layers.

- The encoder processes the input sentence and encodes it into a fixed-length context vector.
- The decoder uses this vector to predict the target sentence word by word.
- Embedding layers and LSTM units are used in both encoder and decoder.
- The model is trained using categorical crossentropy loss and Adam optimizer.
-- Dataset
- Source: [ManyThings.org - fra-eng.zip](http://www.manythings.org/anki/fra-eng.zip)
- We use the file `fra.txt`, placed inside the `data/` folder.
- It contains parallel English–French sentence pairs.





--How to Run This Notebook

1. Clone this repo or download the folder
2. Make sure Python 3.x is installed
3. Install required libraries:
   ```bash
   pip install tensorflow numpy matplotlib scikit-learn





--Sample Output
Model Training Graphs:
Loss and accuracy over epochs

--Sample Translation:
Input: I am a student  
Predicted: je suis étudiant  
Expected: je suis un étudiant