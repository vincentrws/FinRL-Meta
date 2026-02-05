# Notes

Using uv as the venv
`uv venv --python 3.10`

Installed requirements
`uv pip install -e .`

Activate
`source .venv/bin/activate`

Install system dependencies
`sudo apt-get update`
`sudo apt-get install libsdl2-dev libsdl2-image-dev libsdl2-mixer-dev libsdl2-ttf-dev libportmidi-dev libswscale-dev libavformat-dev libavcodec-dev`
`sudo apt-get install swig`

Finally install the requirements in editable mode
`uv pip install -e .`
