Dataset **Total-Text** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/B/a/mQ/ZJS49kSqasqHWLuBKIg6K93QoNI7Rf6xgO3ZMJr4jioSHDVVQMJ0e03egP8gQ90WEvPcp0gpuABom8Fb3QoSATdonhQ2MnekIcSkUZY1G1oVeCXlNSY7WdH82KwN.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Total-Text', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

