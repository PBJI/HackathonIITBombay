# Google image scraper
Hello friends, this is a Google image scraper repository. You can scrap use this to scrap images from Google image, provided the query string.

## Create environment
It is strongly recommended to use a separate environment for this project to avoid any dependency issues with the existing packages.

* create a new virtual environment, get more information [here](https://docs.python.org/3/tutorial/venv.html).
* make sure you have Google chrome installed on your system
* if you want to use this script on a hardware instance, you can use PyVirtualDisplay and wrap the driver into the virtual display, it will also need you to have Xvfb on you system as well.
* install the require packages

> ```pip install requirements.txt```

## Usage
There are two scripts `single_image_per_query.py` and `multiple_image_per_query.py`. 

* to download single image per query use `single_image_per_query.py`
* to download all the images or more than one image per query use `multiple_image_per_query.py`.

