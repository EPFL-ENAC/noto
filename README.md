# noto

Templates to create [noto](https://noto.epfl.ch) kernels. 

# Usage

1. Create a requirements.txt from the templates 
  1. Add additional packages if needed
3. Create a kernel named "my_project": ```kbuilder_create my_project requirements.txt```
4. Open your Jupyter notebook and select the created kernel (my_project)


## geopandas

See ```/geopandas```

We can only have version 0.6.3 of geopandas due to a dependency to pyproj which depends on a preinstalled PROJ version. 
