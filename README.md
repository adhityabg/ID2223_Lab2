# Image Caption generator
### Authors: Adhitya Bharathan Ganesh and Jilei Mao

## Set up
- Download the [Flikr8k_Dataset](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip) and [Flikr8k_text](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip) zip files.
- Unzip them to this folder and remove unnecessary files and folders. The final folder structure should look like
```
|-- <main_folder>
|   |-- Flikr8k_Dataset
|   |   |-- <all the images>
|   |-- Flikr8k_text
|   |   |-- CrowdFlowerAnnotations.txt
|   |   |-- ExpertAnnotations.txt
|   |   |-- Flickr_8k.devImages.txt
|   |   |-- Flickr_8k.testImages.txt
|   |   |-- Flickr_8k.trainImages.txt
|   |   |-- Flickr8k.lemma.token.txt
|   |   |-- Flickr8k.token.txt
|   |-- new_images
|   |   |-- <all the images>
|   |-- main.ipynb
|   |-- model-<....>.h5
|   |-- README.md
|   |-- tokenizer.pkl
```

## Running it
To generate captions for new images just run the commands from Section 5 - Generate captions for new images, from the main.ipynb.