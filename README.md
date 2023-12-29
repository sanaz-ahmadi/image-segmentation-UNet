<ul>
  <li>Employed U-Net to predict a label for every single pixel in an image of the dataset.</li>
  <li>Implemented semantic image segmentation on the CARLA self-driving car dataset.</li>
  <li>Split the dataset into unmasked and masked images and preprocessed it.</li>
  <li>Constructed the U-Net model consisting of an encoder (downsampling block) and a decoder (upsampling block).</li>
  <li>Generated predicted masks using the trained model and applied sparse categorical cross-entropy for pixelwise prediction.</li>
  <li>Visualized model's accuracy and predictions.</li>
</ul>


### steps followed by the code:

1- Load and Split the Data:
    - Split the dataset into Unmasked and Masked Images
    - Preprocess the Data
2- U-Net:
    - Encoder (Downsampling Block) --> conv_block
    - Decoder (Upsampling Block) --> upsampling_block
    - Build the Model --> unet_model
    - Set Model Dimension
    - Loss Function
    - Dataset Handling
3- Train the Model:
    - Create Predicted Masks
    - Plot Model Accuracy
    - Show Predictions


