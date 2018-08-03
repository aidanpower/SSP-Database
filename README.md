# SSP-Database

The Shared Socioeconomic Pathway (SSP) Database categorizes journal articles related to the SSPs. The Database is based upon the work of International Committee On New Integrated Climate change assessment Scenarios or [ICONICS](http://www.cgd.ucar.edu/projects/iconics/publications/), using the citations of each journal article to build a citation network.  

The following files can be used to gather more SSP related articles, visualize the networks as graphs year by year and examine the cominations of SSPs and RCPs used in each artilce.   
 
## INSTALL

Requires Python 3
Requires Pandas and Metaknowledge for the Database, Networkx, Matplotlib, Holoviews and Bokeh for visualization.

```python
# Modules for Matplotlib
import pandas as pd
import metaknowledge as mk
import networkx as nx
import matplotlib.pyplot as plt
import community

from collections import defaultdict

# Modules for Holoviews
import holoviews as hv
import bokeh

from holoviews.operation.datashader import bundle_graph, datashade
hv.extension('bokeh')
```

