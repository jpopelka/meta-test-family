CMD=avocado run --filter-by-tags=-WIP *.py *.sh

check-docker:
	MODULE=docker $(CMD)

check-rpm:
	MODULE=rpm $(CMD)

check: check-docker check-rpm

all: check