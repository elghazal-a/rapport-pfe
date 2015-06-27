How to generate glossary (acr) ?
build rapport.tex
cd Output
makeglossaries rapport
build rapport.tex


\newacronym{yaml}{YAML}{YAML Ain't Markup Language}
\acrlong{yaml} 		=> YAML Ain't Markup Language
\acrshort{yaml} 	=> YAML
\acrfull{yaml}		=> YAML Ain't Markup Language (YAML)

-----------------------------------------------------

How to generate pdf cover ?
build cover/cover.tex
build rapport.tex


-----------------------------------------------------


How to generate index
makeindex Output/rapport.idx
build rapport.tex
