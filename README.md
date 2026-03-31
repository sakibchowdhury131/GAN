# GAN

A collection of Generative Adversarial Network (GAN) experiments implemented in Keras/TensorFlow inside Google Colab notebooks. Includes a DCGAN for generating human face images trained on a custom dataset, and a second experiment generating images of the Eiffel Tower.

## Features

- DCGAN architecture with a convolutional Generator and Discriminator
- Face image generation from a custom personal face dataset
- Eiffel Tower image generation experiment
- Training loop with alternating generator/discriminator updates
- Image visualization during training

## Tech Stack

- Python 3
- Keras / TensorFlow
- NumPy, OpenCV (`cv2`)
- Google Colab

## Project Structure

| File | Description |
|---|---|
| `GAN_FACE_GENERATE.ipynb` | DCGAN trained on a custom face image dataset; produces synthetic face images |
| `GAN_Eiffel_Tower.ipynb` | GAN experiment for generating Eiffel Tower images |

## Requirements

```
tensorflow
keras
numpy
opencv-python
matplotlib
```

## Usage

1. Open either notebook in Google Colab.
2. For `GAN_FACE_GENERATE.ipynb`, upload your image dataset to Google Drive and update `dataset_path` accordingly.
3. Run all cells to train the GAN and visualize generated images.

## License

MIT
