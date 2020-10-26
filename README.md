# sentinel1-rtc
explore sentinel-1 radiometric amplitude public data
https://registry.opendata.aws/sentinel-1-rtc-indigo/

The button below takes you to an interactive JupyterLab session to illustrate cloud-based workflows (computing in the same datacenter where the data is stored AWS us-west-2) without downloading data. 

[![badge](https://img.shields.io/static/v1.svg?logo=Jupyter&label=Pangeo+Binder&message=AWS+us-west-2&color=orange)](https://aws-uswest2-binder.pangeo.io/v2/gh/pangeo-data/notebook-binder/2020.10.26?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fscottyhq%252Fsentinel1-rtc%26urlpath%3Dlab%252Ftree%252Fsentinel1-rtc%252FSentinel1-RTC-example.ipynb%26branch%3Dmain)

Topics covered
1. interactive visualizations with [holoviews](https://holoviz.org/) (band selection, video scrubber, timeseries plot)
1. constructing monthly mosaics for a MGRS tile with [xarray](http://xarray.pydata.org/en/stable/)
1. saving subsets of raster imagery rather than full files
