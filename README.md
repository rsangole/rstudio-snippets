# rstudio-snippets

My useful snippets

```
snippet todo
	# TODO ${0:what}

snippet fm
	format(object.size(), "MB")

snippet ddl
	library(drake); library(data.table); library(lattice) 

snippet gpm
	library(ggplot2); library(plotly); library(magrittr)

snippet ld
	loadd(

snippet rd
	readd(

snippet dmv
	drake::r_make(); drake::r_vis_drake_graph()

snippet dm
	drake::r_make() 

snippet do
	drake::r_outdated() 

snippet ds
	drake::r_sankey_drake_graph(fontSize=15)

snippet dvt
	drake::r_vis_drake_graph(targets_only=TRUE)

snippet dv
	drake::r_vis_drake_graph() 
```
