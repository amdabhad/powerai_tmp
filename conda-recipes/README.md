This directory contains community built recipes for additional conda packages often needed for running deep learning and machine learning python code on POWER. These recipes are automatically built on ppc64le arch from travis-ci.org (https://travis-ci.org/IBM/powerai). Community PRs are welcome. The automatically built packages are published from this conda channel which is hosted at University of Campinas: https://oplab9.parqtec.unicamp.br/pub/ppc64el/power-ai/linux-ppc64le/ .
Add the conda channel like this and then install package:
`conda config --add channels https://oplab9.parqtec.unicamp.br/pub/ppc64el/power-ai/linux-ppc64le/`
`conda install toolchain`
