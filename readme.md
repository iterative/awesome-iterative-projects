[![](https://static.iterative.ai/logo/enterprise.svg)](https://iterative.ai) [![](https://static.iterative.ai/logo/dvc.svg)](https://dvc.org) [![](https://static.iterative.ai/logo/cml.svg)](https://cml.dev) [![](https://static.iterative.ai/logo/studio.svg)](https://studio.iterative.ai)

# Awesome Iterative Projects

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A list of projects relying on [Iterative](https://github.com/iterative) tools to achieve awesomeness.

Missing something awesome? Anyone is welcome to [submit projects to this list](https://github.com/iterative/awesome-iterative-projects/blob/main/contributing.md).

## Tools & Libraries
* [`dvthis`](https://github.com/jcpsantiago/dvthis): Utility functions and project templates for DVC pipelines using R.
* [nvim-dvc](https://github.com/gennaro-tedesco/nvim-dvc): Neovim plugin for DVC.
* [COVID Genomics/Airflow-DVC](https://github.com/covid-genomics/airflow-dvc): Airflow extension for DVC.
* [COVID Genomics/dvc-fs](https://github.com/covid-genomics/dvc-fs): High-level abstraction for DVC file manipulation (listing & I/O) with basic support for [PyFilesystem2](https://github.com/PyFilesystem/pyfilesystem2).
* [zincware/ZnTrack](https://github.com/zincware/ZnTrack): Create, visualize, run & benchmark DVC pipelines in Python & Jupyter notebooks.

## Tutorials
* [DVC Streamlit Example](https://github.com/sicara/dvc-streamlit-example): Build a custom web UI with DVC and Streamlit for visually tracking & comparing model performance during R&D (adapted from [TensorFlow's transfer learning tutorial](https://www.tensorflow.org/tutorials/images/transfer_learning)).
* [DVC Pipelines and Experiments Tutorial](https://github.com/dmesquita/dvc_pipelines_and_experiments_tutorial): Build maintainable Machine Learning pipelines using DVC.
* [CD4ML Example](https://github.com/sbalnojan/cd4ml-example): Example DVC setup with AWS S3 remote storage & GitLab CI/CD.
* [DVC with PyCaret & FastAPI](https://github.com/tezansahu/dvc-pycaret-fastapi-demo): End-to-end demo of data & model tracking (DVC), remote storage (Azure), efficient experimentation (PyCaret) & model deployment (FastAPI).

### Iterative
* [Example-get-started](https://github.com/iterative/example-get-started): Train a `sklearn` random forest classifier for StackOverflow question tagging.
* [Example-DVC-experiments](https://github.com/iterative/example-dvc-experiments): Train a Tensorflow CNN classifier for Fashion-MNIST data; used in https://dvc.org/doc/start/experiments.
* [Example-versioning](https://github.com/iterative/example-versioning): Used in https://dvc.org/doc/use-cases/versioning-data-and-model-files/tutorial.
* [DVC-Checkpoints-MNIST](https://github.com/iterative/dvc-checkpoints-mnist): A showcase for different ways to use the checkpoints. Train a PyTorch classifier on a CSV MNIST dataset.

## Real-world Projects
* [LensKit/lk-demo-experiment](https://github.com/lenskit/lk-demo-experiment): Demo DVC experiment [pipeline (DAG)](https://dvc.org/doc/user-guide/glossary#pipeline-DAG) using multiple public datasets, preprocessing & training, and Jupyter notebooks.
* [ModelOriented/MAIR](https://github.com/ModelOriented/MAIR): Monitoring impact of AI regulations with a DVC pipeline.
* [Kaggle-Titanic-DVC](https://dagshub.com/kingabzpro/kaggle-titanic-dvc): Survival analysis DVC experiment.
* [VQA-With-Multimodal-Transformers](https://github.com/tezansahu/VQA-With-Multimodal-Transformers): Visual Question Answering task on the [DAQUAR Dataset](https://www.kaggle.com/tezansahu/processed-daquar-dataset) using multimodal [transformer models](https://huggingface.co/docs/transformers/index) with an experiment pipeline tracked in DVC Studio.
