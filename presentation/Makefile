
rst_targets:=$(wildcard *.rst)
odp_targets:=$(patsubst %.rst,%.odp,$(rst_targets))

all: $(odp_targets)

%.odp: %.rst template.otp
	rst2odp --template-file=template.otp $< $@

