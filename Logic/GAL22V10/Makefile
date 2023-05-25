GAL=GAL22V10

all:	$(GAL).jed

%.jed:	%.pld
	galasm $<

clean:
	rm *.chp *.fus *.jed *.pin

.phony:	all
