# tensorflow-serving 을 이용한 Deploy 를 다룹니다.

한국어 번역도 합니다~

## tensorflow-serving 이란?

## Overview

### Servable

### Servable Versions

### Servable Streams

### Models

### Loaders

### Sources

### Aspired Versions

### Managers

### Core

## Life of a Servable

![tf serving architecture diagram](https://www.tensorflow.org/serving/images/serving_architecture.svg)	

```bash
# bash from external server	
bazel-bin/tensorflow_serving/example/inception_client --server=104.155.184.157:9000 --image=/path/to/my_cat_image.jpg
```

