# udpipe.models.conll18.baseline - R package containing Universal Dependencies 2.2 Models for UDPipe

NLP models working with udpipe used as the CoNLL18 Shared Task Baseline (http://universaldependencies.org/conll18). These models are made available at <http://hdl.handle.net/11234/1-2859> and are just redistributed here to be able to work with the udpipe R package (https://github.com/bnosac/udpipe) more easily.

The models made available at <http://hdl.handle.net/11234/1-2859> are merely copy-pasted in the [inst/ud-2.2-conll18-baseline-models/models](inst/models) folder and are distributed under the CC BY-NC-SA (http://creativecommons.org/licenses/by-nc-sa/4.0/) licence as indicated by the author of these models [here](https://github.com/ufal/udpipe/issues/79). All non-model related elements from <http://hdl.handle.net/11234/1-2859> have been removed.

More information on these models at the [README](inst/README.txt) and at http://universaldependencies.org/conll18

## Installation

Mark that the size of the package is >900Mb so this might take a while.

```
devtools::install_github("jwijffels/udpipe.models.conll18.baseline")
```

Or install it from www.datatailor.be, which is faster as it is already packaged for you.

```
install.packages("udpipe.models.conll18.baseline", repos = "http://www.datatailor.be/rcube", type = "source")
```
