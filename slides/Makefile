LIST = 1 2

define make-lecture-target
  full$1: slides$1 handout$1 notes$1
  slides$1:
	pdflatex -jobname=slides$1 -output-directory build lecture$1.tex
  handout$1:
	pdflatex -jobname=handout$1 -output-directory build '\PassOptionsToClass{handout}{beamer} \input{lecture$1}'
  notes$1:
	pdflatex -jobname=notes$1 -output-directory build '\PassOptionsToClass{handout,notes=only}{beamer} \input {lecture$1}'

  handouts:: handout$1
  slides:: slides$1
  notes:: notes$1
  all:: full$1
endef

$(foreach l,$(LIST),$(eval $(call make-lecture-target,$l)))
