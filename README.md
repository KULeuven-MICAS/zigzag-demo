# ZigZag Demo

This repository demonstrates ZigZag framework's capabilities and gives a tutorial of how to use it.

To reproduce these notebooks, all you need to have to do is the following:

```
> git clone https://github.com/ZigZag-Project/zigzag-demo.git
> cd zigzag-demo
> conda create -n zigzag python=3.9
> conda activate zigzag
> pip install zigzag-dse
> conda install -c anaconda ipykernel
> python -m ipykernel install --user --name=zigzag
```

Now, ZigZag is installed and it's API is exposed through `from zigzag import api` in your code. Also, the conda environment is exposed to Jupyter Notebook.
You can start your Jupyter Notebook:

```
> jupyter notebook
```

Select the correct conda environment:

![image](https://user-images.githubusercontent.com/55059827/217651717-5370259d-a47a-46a8-b703-3292fefd65dc.png)
