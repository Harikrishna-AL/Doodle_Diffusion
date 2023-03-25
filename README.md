# Doodle Diffusion
This project aims to build a diffusion based that generates google doodles from given prompts. The Reverse diffusion process is done using a UNet model which takes noised image, timestamp and text as input. The timestamp is embedded into the model using SineCosine Embedding and the text is encoded using a CLIP encoder and then added to the noised image.

# Limitations
The outputs are still not very satisfactory as the dataset didn't contain enought images for many of the events. Also, I had limited access to GPU on kaggle. But this can be done with better dataset and hardwaare resources.
# Generated output for the text "world cup" 
<img src="/images/Screenshot from 2023-03-19 17-02-44.png">
