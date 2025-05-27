## 📦 Project Overview

This project is a modified version of an existing open-source CNN classifier for the MNIST dataset. I extended the original implementation by adding additional convolutional and pooling layers, recalculating layer dimensions, and ensuring the model runs smoothly with the updated architecture.

## 🔄 Modifications Made

- Added a third convolutional layer (128 output channels)
- Integrated max pooling layers after each convolutional block
- Recalculated input size for the first fully connected layer (changed from 9216 to 1152)
- Adjusted model forward pass to accommodate the new structure

## 🧾 Credit

This work is based on an open-source project from [GitHub](https://github.com/pytorch/examples) with contributions from multiple authors. Full credit goes to the original contributors for their foundational implementation.

> If you're one of the contributors and would like to be named directly, feel free to reach out!
