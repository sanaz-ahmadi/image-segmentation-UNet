<ul>
  <li>Employed U-Net to predict a label for every single pixel in an image of the dataset.</li>
  <li>Implemented semantic image segmentation on the CARLA self-driving car dataset.</li>
  <li>Split the dataset into unmasked and masked images and preprocessed it.</li>
  <li>Constructed the U-Net model consisting of an encoder (downsampling block) and a decoder (upsampling block).</li>
  <li>Generated predicted masks using the trained model and applied sparse categorical cross-entropy for pixelwise prediction.</li>
  <li>Visualized model's accuracy and predictions.</li>
</ul>


### steps followed by the code:
<ul>
  <li>1- Load and Split the Data:
    <ul>
      <li>Split the dataset into Unmasked and Masked Images</li>
      <li>Preprocess the Data</li>
    </ul>
  </li>
  <li>2- U-Net:
     <ul>
      <li>Encoder (Downsampling Block) --> conv_block</li>
      <li>Decoder (Upsampling Block) --> upsampling_block</li>
      <li>Build the Model --> unet_model</li>
      <li>Set Model Dimension</li>
      <li>Loss Function</li>
      <li>Dataset Handling</li>
    </ul>
  </li>
  <li>Train the Model:
    <ul>
      <li>Create Predicted Masks</li>
      <li>Plot Model Accuracy</li>
      <li>Show Predictions</li>
    </ul>
  </li>
</ul>



