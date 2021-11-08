.PHONY: all
all: application.pdf

DEPENDS+=	bibedu.sty
DEPENDS+=	bibedu.bib

application.pdf: application.tex project.tex
application.pdf: ${DEPENDS}

PREWC=pandoc -f latex -t markdown

wc: project.tex


INCLUDE_MAKEFILES=../../../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
include ${INCLUDE_MAKEFILES}/doc.mk
INCLUDE_BIBEDU=../../../bibedu
include ${INCLUDE_BIBEDU}/bibedu.mk
