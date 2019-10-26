sources = $(wildcard *.less)
targets = $(sources:.less=.css)

LESSC = lessc
LESSC_FLAGS =

.PHONY: all
all: $(targets)

%.css: %.less
	$(LESSC) $< $@ $(LESSC_FLAGS)

.PHONY: clean
clean:
	rm -f $(targets)
