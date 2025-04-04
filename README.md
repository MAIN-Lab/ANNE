# ANNE
ANNE: The Adaptive Neuron Network Expansion for Medical Image Segmentation


<p align="center">
  <figure>
    <img width="750" src="images/NExNetSeg_detailed.png" alt="NexNetSeg Architecture">
    <figcaption>Illustration of the proposed ANNE architecture for medical image segmentation. The encoder blocks are composed of a sequence of dilated convolutions and Mamba blocks, which are used to capture both local and global context from the input tensor effectively. The context-enriched features are then passed through the proposed A-PEN blocks to enhance feature representation by adaptively expanding each neuron to better approximate the target function. In the decoder section, A-PEN blocks are used for initial upsampling, followed by regular transpose convolution layers in the later stages to reconstruct the final segmentation output.</figcaption>
  </figure>
</p>


# UNDER CONSTRUCTION
### In the meantime, here is a picture of a 
<p align="center">
  <figure>
    <img width="700" src="images/quokka.jpg" alt="quokka">
    <figcaption>Happy quokka.</figcaption>
  </figure>
</p>

## License
See the [LICENSE](LICENSE.md) file for license rights and limitations (MIT).

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
