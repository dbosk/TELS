.PHONY: all
all: notes.pdf

LATEXFLAGS+=	-shell-escape

SRC+=		preamble.tex
DEPENDS+=	bibliography.bib

SRC+=		active.tex
DEPENDS+=	active.bib

SRC+=		testing.tex
SRC+=		trying-first.tex


notes.pdf: notes.tex
notes.pdf: ${SRC}


.PHONY: clean
clean:
	${RM} notes.pdf


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
