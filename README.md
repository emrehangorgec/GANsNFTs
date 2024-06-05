# Generative Art NFTs

## Description
This repository contains the implementation of a pipeline for generating artistic style transfers and automating NFT minting using the Crossmint API. The project aims to explore the intersection of AI-generated art and blockchain technology, providing a streamlined process for artists and creators to mint their artworks as NFTs on various blockchain platforms.

## Features
- **Style Transfer**: Utilize StyleGAN3 models with the neural style transfer techniques to apply artistic styles to digital images.
- **NFT Minting**: Integrate with Crossmint to mint the generated images as NFTs directly.
## Sample Output
Below are some examples of the artistic style transfers applied using StyleGAN3. These examples demonstrate the potential of the project for creators interested in AI-generated art and blockchain technology.

Prompt: "A close-up portrait of a Scottish Fold cat with an expressive face and folded ears prominently displayed. The cat has a soft, silver-blue coat and deep, thoughtful eyes. The background is a simple, muted color to keep the focus on the intricate details of the cat’s fur and unique features."


![rocco_cubism](https://github.com/emrehangorgec/GANsNFTs/assets/54534150/fe3f4dec-3717-493c-845f-011e226789a3)

----------------------------------------------------------------------------------------------------------

![image_4](https://github.com/emrehangorgec/GANsNFTs/assets/54534150/434e8679-7acc-4e4a-a9ac-c9d6e2a94f89)


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

