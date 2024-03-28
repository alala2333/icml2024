# icml2024
* Image Fusion Framework
  * We have extended our PDF to image fusion with feature interaction. Considering the properties of image fusion, we transformed the predicted $p_{true}$ to the gradient obtained by backpropagation, to get Mono Confidence(MC). Based on the positive correlation between gradient and loss, we construct reliable multimodal fusion weights by gradient that satisfy the generalization theory to integrate multimodal features. 
   ![img](https://github.com/alala2333/icml2024/blob/main/image_fusion_frame.png)

* Comparison between other image fusion methods.
  * We compared the fusion results of our method and other methods, and it's clear that the fusion results obtained by our method are richer in detail, with little distortion of color. These experiments fully demonstrated our superiority against the state-of-the-art methods.
  ![img](https://github.com/alala2333/icml2024/blob/main/Comparison_260535.png)
  ![img](https://github.com/alala2333/icml2024/blob/main/Comparison_210295_new.png)
