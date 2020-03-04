# Pokemon USUM Texture Mirror and Waifu2x Upscaler

The first python script iterates through a directory and finds every .png with a particular pattern and mirrors it accordingly, while the second python script applies TWO waifu-2x transformations, upscaling the USUM textures to 1080p quality.

WARNING: These directly replace the .png files rather than making copies.  Please make sure you have a backup of your extracted directory before using this script incase you change your mind!

- Support for Sw/Sh will be included shortly!

These transformations were used on the exported USUM models and textures as part of the fan game Pokemon Infinite.  

--------------

# transform.py

- You will need to create a `venv` and install the `PILLOW` module in your virtual environment in order for `transform.py` script to function properly.  This can be done with `pip install pillow`.

- On line 8, where it says `for subdir, dirs, files in os.walk(os.path.expanduser('~danieljsottile/Desktop/TEST')):`, replace the directory with YOUR full pathname for your extracted directory.  This python script does NOT need to be in the same folder as your files.  In this particular example, my directory was named `TEST`, but it will likely be called `SMD` if you use the pyautogui script to extract the models.

-------------

# waifu2x-model.py

- You will need ???? in order for the `waifu2x-models.py` script to function properly.