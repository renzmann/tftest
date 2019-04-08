# tftest

Simple python scripts for testing if TensorFlow is using GPU.

## How to use

Set up an empty conda environment:

```sh
$ conda create -ny tftest python=3.7
```

Install tensorflow-gpu

```sh
$ conda activate tftest
(tftest) $ conda install -y tensorflow-gpu
```

Check that the gpu is listed:

```sh
(tftest) $ python list.py
```

Try a simple tensorflow operation:

```sh
(tftest) $ python tftest.py
```
