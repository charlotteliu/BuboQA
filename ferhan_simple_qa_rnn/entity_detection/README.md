## Entity Detection

### How to use

run the script
```
bash get_data.sh
```
to get data.

- You will require the package - [torchtext](https://github.com/pytorch/text).
```
git clone https://github.com/pytorch/text.git
cd path/to/torchtext
python setup.py install
```


```
python3.6 train.py --no_cuda
or
python3.6 train.py
```

to train the model. You should stop the training process manually when you want to terminate it.

```
python3.6 main.py --trained_model [path/to/trained_model.pt]
```

to test the model.

### Preprocessing

Training data can be generated by running script

```
python3.6 preprocess.py
```

### preliminary Result

Run 30 epoch.
DEV  86.75%
TEST 86.38%

### To Do

Output or Logging should be improved.
