# clip-search
Experimenting with text to image models, inspired by the National Library of Norway's [Maken Clip Text](https://huggingface.co/spaces/NbAiLab/maken-clip-text) project.

## Setup & Environment

### OS X M1 Apple Silicon
```
conda create --name clipsearch python=3.9     
conda activate clipsearch
conda install -c anaconda ipykernel
conda install -c conda-forge sentence-transformers
pip install ftfy spacy
pip install notebook ipywidgets widgetsnbextension
python -m ipykernel install --user --name=clipsearch
jupyter notebook
```
(Switch your active kernel to `clipsearch`)
