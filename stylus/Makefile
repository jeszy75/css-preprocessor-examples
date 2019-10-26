sources = $(wildcard *.styl)
targets = $(sources:.styl=.css)

STYLUS = stylus
STYLUS_FLAGS =

.PHONY: all
all: $(targets)

%.css: %.styl
	$(STYLUS) $< $(STYLUS_FLAGS)

.PHONY: clean
clean:
	rm -f $(targets)

