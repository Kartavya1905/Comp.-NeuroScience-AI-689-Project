# Robust Neural Decoding

This project uses neural signals to predict finger movements.

## Dataset

Download Dataset 4 here:

https://www.bbci.de/competition/iv/#dataset4

Extract the ZIP file and place the extracted `.mat` files in the same folder as the code.

Example:

```text
project-folder/
├── sub1_comp.mat
├── sub2_comp.mat
├── sub3_comp.mat
├── project_code.ipynb

# Models Used
Wiener Filter
Neural Network

Evaluation
The models are compared using R² score and channel dropout testing.

Result
The Neural Network performs better than the Wiener Filter.
