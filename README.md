# ZigZag Demo

This repository demonstrates ZigZag framework's capabilities and gives a tutorial of how to use it.

To reproduce these notebooks, all you need to have to do is the following:

```
> git clone https://github.com/ZigZag-Project/zigzag-demo.git
> cd zigzag-demo
> conda create -n zigzag python=3.9
> conda activate zigzag
> pip install zigzag-dse
> conda install -c anaconda ipykernel jupyter
> python -m ipykernel install --user --name=zigzag
```

Now, ZigZag is installed and it's API is exposed through `from zigzag import api` in your code. Also, the conda environment is exposed to Jupyter Notebook.
You can start your Jupyter Notebook:

```
> jupyter notebook
```

Select the correct conda environment:

![image](https://user-images.githubusercontent.com/55059827/217651717-5370259d-a47a-46a8-b703-3292fefd65dc.png)


## Content
- [Demo1](https://github.com/ZigZag-Project/zigzag-demo/blob/main/Demo1.ipynb): Run a DNN on an accelerator, get energy and latency breakdown.
- [Demo2](https://github.com/ZigZag-Project/zigzag-demo/blob/main/Demo2.ipynb): Hardware architecture comparison.
- [Tutorial1](https://github.com/ZigZag-Project/zigzag-demo/blob/main/Tutorial1.ipynb): The inputs and outputs of ZigZag - a single-layer example run.
- [Tutorial1 advance](https://github.com/ZigZag-Project/zigzag-demo/blob/main/Tutorial1_advance.ipynb): The inputs and outputs of ZigZag - a multi-layer example run, with different layer types and residual/branch connection.
- [Tutorial2](https://github.com/ZigZag-Project/zigzag-demo/blob/main/Tutorial2.ipynb): Look into the ZigZag API function.

