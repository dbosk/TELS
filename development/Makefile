.PHONY: all
all: application-2021.pdf

DEPENDS+=	bibedu.sty
DEPENDS+=	bibedu.bib

application-2021.pdf: ${DEPENDS}


INCLUDE_MAKEFILES=../../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
INCLUDE_BIBEDU=../../bibedu
include ${INCLUDE_BIBEDU}/bibedu.mk
