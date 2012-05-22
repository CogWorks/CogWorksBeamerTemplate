========================
CogWorks Beamer Theme(s)
========================

------------
Installation
------------
This should work MacOX and Linux::

	make install

or::

	export TEXMFHOME=$(cat $(kpsewhich texmf.cnf) | grep "^TEXMFHOME" | cut -f 3 -d " ")
	mkdir -p ${TEXMFHOME}/tex/latex/beamer/base/themes/theme
	mkdir -p ${TEXMFHOME}/tex/latex/beamer/base/art
	cp beamerthemeCogWorks.sty ${TEXMFHOME}/tex/latex/beamer/base/themes/theme/
	cp cwl-header.png ${TEXMFHOME}/tex/latex/beamer/base/art/
