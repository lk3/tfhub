# Tensorflow tests using Tensorflow Hub models

The contents of this repository are experimental.

## Sentiment

Create and activate environment:
```
conda env create -f ~/tfhub/sentiment.yml
conda activate sentiment
```

Start Jupyter and run the notebook:
```
export KERAS_BACKEND=tensorflow MEM_LIMIT=100000000; jupyter notebook --port=8888 --ip=0.0.0.0
```

MEM_LIMIT is not enforced, only for reference purposes.