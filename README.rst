========================
CogWorks Beamer Theme(s)
========================

------------
Installation
------------
This should work MacOX and Linux::

	mkdir -p ${TEXMFHOME}/tex/latex/beamer/base/themes/theme
	mkdir -p ${TEXMFHOME}/tex/latex/beamer/base/art
	cp beamerthemeCogWorks.sty ~/.texmf/tex/latex/beamer/base/themes/theme/
	cp cwl-header.png ~/.texmf/tex/latex/beamer/base/art/

If you need help finding TEXMFHOME try::

	cat `kpsewhich texmf.cnf` | grep "^TEXMFHOME"

or::

	tlmgr conf | grep "TEXMFHOME"
