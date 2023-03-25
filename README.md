# Doodle Diffusion
This project aims to build a diffusion based that generates google doodles from given prompts. The Reverse diffusion process is done using a UNet model which takes noised image, timestamp and text as input. The timestamp is embedded into the model using SineCosine Embedding and the text is encoded using a CLIP encoder and then added to the noised image.
