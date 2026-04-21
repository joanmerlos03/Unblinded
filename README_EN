# Unblinded

This project, developed by Axel Valton Juan and Joan Merlos Cremades, has consisted of developing software that can read text, describe landscapes, guide the user in a specific direction, and search for objects, with the intention of making the day-to-day lives of visually impaired people easier. For this project to be properly finalized, these functions would need to be implemented on a device equipped with a camera, microphone, and GPS, connected to a pair of headphones. However, in our case, we have limited ourselves to developing the code so that it is functional on a conventional computer.

The developed code files are:

* `Unblinded_Script.py`: This is the main script of the code that allows us to choose between the different modes of our device, these being **Reading**, **Description**, **Guided Navigation** (a mode has been implemented that simulates a person's journey along a given route), and **Search** (which is located in the `Unblinded_busqueda.ipynb` file).
* `Unblinded_Functions.py`: This is the secondary script that contains all the functions that allow the program to work. It is worth noting that these functions use different models such as gTTS to convert text to speech, Whisper to process the audio, Google Maps to obtain routes, and various Llama generative AI models to process both images and text.
* `Unblinded_busqueda.ipynb`: This file allows us to obtain a detailed description of the spatial position of a mentioned object. It should be noted that this mode is located in a separate file because it uses the SAM3 model, which requires a graphics card to function. Given this situation, we have chosen to program this mode in a notebook that can be easily executed from the Google Colab platform.
