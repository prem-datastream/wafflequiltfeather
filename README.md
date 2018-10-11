# wafflequiltfeather
A repository to test whether the combo of waffle quilt and feather will be able to slice data appropriately for precision medicine

[![Waffle.io - Issues in progress](https://badge.waffle.io/prem-datastream/wafflequiltfeather.png?label=in%20progress&title=In%20Progress)](http://waffle.io/prem-datastream/wafflequiltfeather)

```###Testing:  

#Install quilt

pip install quilt

downgrade pyarrow to 10 (otherwise there may be an error in putting the data into the dataframe)

pip install pyarrow==0.10.0

#Import data

quilt install uciml/iris

>>> from quilt.data.uciml import iris

>>> df = iris.tables.iris()

```

