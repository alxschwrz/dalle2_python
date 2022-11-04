<h1 align="center">dalle2_python </h1>

<p align="center">
   Generating stunning images from the command line.
</p>

This is a simple working example on how to integrate the DALLE2 API into your own Python project and create amazing images directly from the command line.

## How it works
Reads a string from the command line in natural language and creates as an input prompt which is then fed to OpenAIs DALLE2. The response contains urls to the generated images. The images are downloaded and stored in an output folder.
To generate your own images you need to get access to the DALLE2 API (https://openai.com/dall-e-2/).

## Installation
```bash
git clone https://github.com/alxschwrz/dalle2_python.git
cd dalle2_python
pip3 install -r requirements.txt
```

## Run example
Reads an input prompt from the terminal and stores the generated images in the output folder.
```
python3 dalle2_python.py
```

Input your prompt and check the images in the output folder ;)



How to use it
```python
from dalle2_python import CommandLineDalle

dalle = CommandLineDalle(img_sz="1024", n_images="4")
dalle.generate_and_save_images()
dalle.open_urls_in_browser()
```
