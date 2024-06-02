# Generative Art NFTs

## Description
This repository contains the implementation of a pipeline for generating artistic style transfers and automating NFT minting using the Crossmint API. The project aims to explore the intersection of AI-generated art and blockchain technology, providing a streamlined process for artists and creators to mint their artworks as NFTs on various blockchain platforms.

## Features
- **Style Transfer**: Utilize StyleGAN3 models with the neural style transfer techniques to apply artistic styles to digital images.
- **NFT Minting**: Integrate with Crossmint to mint the generated images as NFTs directly.
## Sample Output
Below are some examples of the artistic style transfers applied using StyleGAN3. These examples demonstrate the potential of the project for creators interested in AI-generated art and blockchain technology.

![image](https://github.com/emrehangorgec/GANsNFTs/assets/54534150/b1a76bc4-9d96-4786-90dc-7742c4b3a66e)
Prompt: “An adorable Yorkshire Terrier playing in a vibrant garden filled with colorful flowers and green grass. The dog is small, with a shiny, silky coat and a neatly trimmed haircut. It is playfully chasing butterflies under a sunny, clear blue sky.”

![image](https://github.com/emrehangorgec/GANsNFTs/assets/54534150/dab7aeb3-d878-40ae-9183-5ebd3d1c50a2)

The model that is trained with the Cubism dataset from [WikiArt](https://www.kaggle.com/datasets/steubk/wikiart) can be found in the following link:
[Cubism 256x256, pretrained model](https://www.kaggle.com/datasets/emrehangrge/cubism256x256-stylegan3)
### Libraries and Packages:
- openai
- ninja
- ipywidgets
- requests
- pinata
- Python Version: 3.10.12 
- TensorFlow Version: 2.15.0
- PyTorch Version: 2.3.0+cu121

