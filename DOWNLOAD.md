Dataset **Сonstruction Equipment** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/O/y/bp/dRTEfOgywQFdl8h5mvYr4msZMehMrfeMGATmSYIetjnXxdpv8n8T4fQeCdGGYjIDItkTgZTeNjfrAvUTk38gYM96DrMkDw8B73g0nPNaB9gRaCxpoG6L6zS7Vg9b.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Сonstruction Equipment', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

