Dataset **Construction Equipment** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI4MzFfQ29uc3RydWN0aW9uIEVxdWlwbWVudC8yMjY5XzI4MzFfQ29uc3RydWN0aW9uIEVxdWlwbWVudC50YXIiLCAic2lnIjogImczdE9Yc3FPb29wM0IvSUxDMFh2YjdUMWs1VEhHa3dTUFV3WmpYM2hhbzQ9In0=)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Construction Equipment', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/kartaviychert/arh-df).