for 2.4
# Makefile

all: init destroy set check

init: init.cpp
	g++ init.cpp -o init

destroy: destroy.cpp
	g++ destroy.cpp -o destroy

set: set.cpp
	g++ set.cpp -o set

check: check.cpp
	g++ check.cpp -o check

clean:
	rm -f init destroy set check
