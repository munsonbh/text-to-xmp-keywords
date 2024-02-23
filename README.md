# Text to XMP Keywords

Takes text files made from a keyword generator (such as what you get from the Stable Diffusion utilities in [kohya_ss](https://github.com/kohya-ss/sd-scripts)) and inserts them into image XMP metadata. Uses the EXIFtool CLI to do the dirty work.

## Dependencies
CLI
- [EXIFtool](https://github.com/exiftool/exiftool)

Python Libraries (pip install)
- [jupyter](https://github.com/jupyter/notebook) or [jupyter-lab](https://github.com/jupyterlab/jupyterlab)
- os
- subprocess

## Howto
1. Make some comma-separated keyword text files that are named the same as the image file they correspond with
1. Make sure those text files are in the same folder as your images (standard for keyword generators)
1. Open the notebook and change the path in the first block to your image folder
1. Run the codes

## 99% made by AI
I simply interrogated the JupyterLab OpenAI plug-in until it worked, then moved the folder path to an easier place to change. I'm a dumb-but-tenacious designer. Enjoy!