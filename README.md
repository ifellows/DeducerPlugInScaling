# DeducerPluginScaling
A Deducer plug-in for factor analysis, reliability analysis and discriminant analysis, using psych, GPArotation  and mvnormtest packages.


# Usage

See: http://www.deducer.org


# Building and installing
Get the released version from CRAN:

```R
install.packages("DeducerPlugInScaling")
library(JGR)
launchJGR(jgrArgs="--withPackages=DeducerPlugInScaling")
```

To build from this repository

```
R CMD build DeducerPlugInScaling
R CMD INSTALL DeducerPlugInScaling_*.*.tar.gz
```

Or simply

```R
# install.packages("devtools")
devtools::install_github("ifellows/DeducerPlugInScaling")