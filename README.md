# QR Code Generation with Stable Diffusion

![MechanicalGirl](/Output/Mechanical%20girl_2.png)

![Cyborg](/Output/cyborg.png)

![Maps](/Output/maps.png)

![Mountain](/Output/mountains.png)

![Robot](/Output/Robot.png)

## Approach

1. Generate a QRCode with the URL you want to Embed?
2. Load the Pretrained Control Net QR Code Model
3. Setup the Control Net pipeline with the pretrained model
4. Provide Prompts and Negative Prompts for how the QRcode should look like.
5. Run the Pipeline with different hyperparameters and prompts.

## Acknowledgement

Control Model used - [DionTimmer](https://huggingface.co/DionTimmer/controlnet_qrcode-control_v1p_sd15)

Stable Diffusion Model used - [GhostMix](https://huggingface.co/digiplay/GhostMixV1.2VAE)

A Special Mention to [Abhishek Thakur](https://www.linkedin.com/in/abhi1thakur/), I used his video as reference to generate these outputs.
