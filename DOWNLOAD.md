Dataset **Pothole Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/D/k/2h/tvsp8w1UCao9nvWkEJINWN064V0MpRjFLT55mP93qfmoV4Pwmmf8ekDk8KU3Jl8Jch7KqlbwRRGu73mlOhbHW2l1dA3d7oleHFLsRcf91d3lR6sF7lq7SZVfHQz3.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Pothole Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

