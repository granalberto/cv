# Makefile para la creación de documentos
export SP_ENCODING=UTF-8


all: ajmp-cv.ps ajmp-cv.pdf


ajmp-cv.ps: ajmp-cv.sgml
	docbook2ps -d style.dsl ajmp-cv.sgml


ajmp-cv.pdf: ajmp-cv.sgml
	docbook2pdf -d style.dsl ajmp-cv.sgml
