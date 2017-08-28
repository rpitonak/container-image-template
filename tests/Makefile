# TODO: commented becasue MTF generates enormous amount of logs
# CMD=avocado run --show-job-log
CMD=avocado run
MODULELINT=/usr/share/moduleframework/tools/modulelint/*.py

check:
	MODULE=docker $(CMD) $(MODULELINT)

all: check
