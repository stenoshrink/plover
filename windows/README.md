# Windows Development

## Environment setup

You need Python 3.6 (32 bits) installed with pip support.

For installing all the required dependencies, you can use:

`python -m pip install -r requirements.txt`

To install the standard plugins, you can use:

`pip3 install --user -e . -r requirements_plugins.txt`

## Development helpers

* `./launch.bat`: run from source
* `./test.bat`: run tests
* `./setup.py bdist_win`: create a standalone distribution
