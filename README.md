# ray-scale
This repo has code snippets for using ray in your ML projects

## ray data

```bash
pip install -U "ray[data]"
```

You can scale data processing and batch inference

Use cases ray data helps with are:
1. Large scale batch inference where data processing happens on CPU and inference on GPU
2. Distributed training where again data processing happens on CPU and training on GPU

How ray data process large scale datasets? It uses streaming execution
