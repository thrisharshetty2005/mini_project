The project explored the application of deep learning models—CNNs, RNNs, and GANs—for image classification, sequence learning, and generative modeling. For image classification, two CNN architectures were implemented: a custom CNN with convolution, ReLU, pooling blocks, and BatchNorm/Dropout, and a transfer learning model using ResNet18. The models were trained on the Fashion-MNIST dataset, with evaluations including accuracy, confusion matrices, training/validation curves, model size, and training time. 

For sequence learning, a baseline RNN, along with LSTM and GRU variants, were applied to a time-series prediction task. Models were compared using RMSE, convergence behavior, and stability of loss curves, demonstrating the superior performance and stability of GRU over vanilla RNN and LSTM. 

Generative modeling was performed using a GAN to synthesize Fashion-MNIST images. The generator and discriminator were trained alternately, and outputs were saved periodically to track sample quality. Model collapse was observed occasionally and mitigated via learning rate adjustment and label smoothing. 

How to Run The Code:
1.Open Google Colab
2.Go to runtime->change runtime->T4 GPU
3.Type the code and run

 
