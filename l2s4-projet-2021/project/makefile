ARCHIVE_FILES=$(wildcard jar/* test/* documents/* src/*) manifesthumanwar manifesthumanfarm manifestfarm manifestwar Makefile README.md
PACKAGE = game
DELETE = classes docs

all: cls doc



doc: 
	cd src && javadoc  -d ../doc

cls:
	cd src && javac -d ../classes $(PACKAGE)/*.java


clean:
	rm -r $(DELETE)
	
.PHONY: all clean doc cls

.ONESHELL:

