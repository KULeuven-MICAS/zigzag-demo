This repository gives a first glimpse into the possibilities of using ZigZag.

We demonstrate a part of its flow in two jupyter notebooks:

- A comparison of different architectures in `architectures.ipynb`.
- A breakdown of a single architecture across layers for energy and latency inspection in `breakdown.ipynb`.

To reproduce these notebooks, all you have to do is the following:

```
> conda create -n my-env python=3.9
> conda activate my-env
> pip install zigzag-dse 
```

Now, ZigZag is installed and it's API is exposed through `from zigzag import api` in your code.