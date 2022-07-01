.PHONY: all
all: notes.pdf

LATEXFLAGS+=	-shell-escape

SRC+=		preamble.tex
SRC+=		testing.tex
SRC+=		trying-first.tex

notes.pdf: notes.tex
notes.pdf: ${SRC}


.PHONY: clean
clean:
	${RM} notes.pdf


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
