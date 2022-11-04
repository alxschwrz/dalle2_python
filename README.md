<h1 align="center"> 📸 dalle2_python 🏞 </h1>

<p align="center">
   Generating stunning images from the command line.
</p>

This is a simple working example on how to integrate the DALLE2 API into your own Python project and create amazing images directly from the command line.

## How it works
Reads a string from the command line in natural language and creates an input prompt which is then fed to OpenAIs DALLE2. The response contains urls to the generated images. The images are downloaded and stored in an output folder.
To generate your own images you need to get access to the DALLE2 API (https://openai.com/dall-e-2/).

## Installation
```bash
git clone https://github.com/alxschwrz/dalle2_python.git
cd dalle2_python
pip3 install -r requirements.txt
```

## Run example
```
python3 dalle2_python.py
What image should dalle create: if running late for class was an animal, digital art
Generated image stored in: ./output/if running late for class was an animal, digital art_0.png
Generated image stored in: ./output/if running late for class was an animal, digital art_1.png
```
Now check the output folder:
<p float="left">
<img src="/output/if running late for class was an animal, digital art_0.png" alt="example_of_prompt_in_terminal" width="200"/>
<img src="/output/if running late for class was an animal, digital art_1.png" alt="example_of_prompt_in_terminal" width="200"/>
</p>

Enjoy!
