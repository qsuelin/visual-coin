# Visual-coin
Visual-coin is a Python console application for visualizing metrics of different blockchain asset in the form of graph or animation. The data sources from coinmetrics api V2.

## API reference
### Synopsis
visual-coin.py [-h] --assets ASSETS [ASSETS ...] [--output {png,pdf,mp4,gif,mov,avi} [{png,pdf,mp4,gif,mov,avi} ...]] [--dir DIR] [--name NAME] [--quiet]



### Options
<dl>
  <dt>-assets | -a opt1 [opt2 ...]
  <dd>Input asset(s) to be visualized into a single graph. If many, separated with space
  <dd> Check coinmetrics for supported assets. If asset is invalid or failed to connect to the server, exception will be raised.

  <dt>--output | -o opt1 [ opt2 ...]
  <dd>Input the file type(s) to export as. If many, separated with space.
  <dd>Supported format: png, pdf, mp4, gif, mov, avi

  <dt>--dir | -d DIR
  <dd>Input destination directory to export files into.

  <dt>--name | -n NAME
  <dd>Input desired filename. Default: assetid1_assetid2_...%y%m%d.filetype

  <dt>--quite | -q
  <dd>If specify, the graph will be drawn as daemon.
<dl>
