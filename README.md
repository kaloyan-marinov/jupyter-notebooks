```
$ python3 --version
Python 3.8.3

$ python3 -m venv venv
$ source venv/bin/activate
(venv) $ pip install --upgrade pip
(venv) $ pip install -r requirements.txt

(venv) $ jupyter lab
```

---

[This StackOverflow post](
    https://stackoverflow.com/questions/50982686/what-is-the-difference-between-jupyter-notebook-and-jupyterlab/
) says:
> Jupyter Notebook is a web-based interactive computational environment for creating Jupyter notebook documents... it just consists of a filebrowser and an (notebook) editor view.

> JupyterLab is the next-generation user interface <b>including notebooks</b>. It has a modular structure, where you can open several notebooks or files (e.g. HTML, Text, Markdowns etc) as tabs in the same window. It offers more of an IDE-like experience.