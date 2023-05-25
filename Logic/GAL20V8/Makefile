GAL=GAL20V8

all:	$(GAL).jed

%.jed:	%.pld
	galasm $<

clean:
	rm *.chp *.fus *.jed *.pin

.phony:	all
