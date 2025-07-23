<div align="center">
  <h1>
    🧠 Artificial Intelligence - Computer Assignment 4 🖼️
  </h1>
  <h2>
    Image Classification with Neural Networks
  </h2>
  <p>
    This project is the fourth assignment for the Artificial Intelligence course. The primary goal is to implement, train, and compare two types of neural networks—<strong>Fully Connected</strong> and <strong>Convolutional</strong>—for an image classification task using the <strong>PyTorch</strong> library.
  </p>
</div>

<hr>

### 📖 Dataset: CIFAR-10
The project uses the well-known **CIFAR-10** dataset. It consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The dataset is pre-split into 50,000 training images and 10,000 testing images.

<hr>

<table>
  <tr>
    <td valign="top" width="50%">
      <h2>
        Part 1: Fully Connected Neural Network
      </h2>
      <p>
        The first part of the assignment involves building a traditional <strong>Fully Connected Neural Network (FCNN)</strong> to classify images from the CIFAR-10 dataset. The input images are flattened into vectors, and the network learns to classify them based on these pixel values.
      </p>
      <details>
        <summary>
          <strong>Implementation Steps</strong>
        </summary>
        <ul>
          <li>
            <strong>Network Architecture</strong>: Design an FCNN with a specific constraint that the number of trainable parameters must be approximately <strong>3,500,000 ± 500,000</strong>. Techniques like Dropout can be used to prevent overfitting.
          </li>
          <li>
            <strong>Parameter Calculation</strong>: Manually calculate the number of parameters in the designed network and compare it with the output from the PyTorch model summary.
          </li>
          <li>
            <strong>Loss Function & Optimizer</strong>: Use the <strong>Cross-Entropy Loss</strong> function and the <strong>Adam optimizer</strong> for training.
          </li>
          <li>
            <strong>Training & Evaluation</strong>: Train the model for <strong>60 epochs</strong>, recording training and validation loss/accuracy at each epoch. Plot these values to analyze model performance and check for overfitting.
          </li>
          <li>
            <strong>Final Assessment</strong>: Evaluate the final model on the test dataset.
          </li>
        </ul>
      </details>
    </td>
    <td valign="top" width="50%">
      <h2>
        Part 2: Convolutional Neural Network
      </h2>
      <p>
        This part involves implementing a <strong>Convolutional Neural Network (CNN)</strong> to solve the same classification problem. The goal is to leverage the spatial hierarchy of images for better feature extraction and performance compared to the FCNN.
      </p>
      <details>
        <summary>
          <strong>Implementation Steps</strong>
        </summary>
        <ul>
          <li>
            <strong>Network Architecture</strong>: Design a CNN with a comparable number of trainable parameters (<strong>~3,500,000</strong>) to ensure a fair comparison with the FCNN.
          </li>
          <li>
            <strong>Training & Comparison</strong>: Train the CNN for <strong>60 epochs</strong> using the same loss function and optimizer. Compare its performance (loss and accuracy curves) with the FCNN and analyze the differences.
          </li>
          <li>
            <strong>Error Analysis</strong>: Visualize 24 images that the model misclassified, showing both the predicted and actual labels.
          </li>
          <li>
            <strong>Feature Space Analysis</strong>:
            <ul>
              <li>Use the K-Nearest Neighbor algorithm to find and visualize the 5 closest neighbors for 5 correctly classified test images in the feature space.</li>
              <li>Use <strong>t-SNE</strong> to reduce the dimensionality of the feature space to 2D and visualize the clustering of the data.</li>
              <li>Visualize the intermediate **Feature Maps** from the convolutional layers to understand what the network is "seeing".</li>
            </ul>
          </li>
        </ul>
      </details>
    </td>
  </tr>
</table>

<hr>

