SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/dut.v
VERILOG_SOURCES += $(PWD)/../wrapper/test_dut.v
TOPLEVEL = test_dut
MODULE = dut_test
xor:
	$(MAKE) sim MODULE=dut_test TOPLEVEL=test_dut
include $(shell cocotb-config --makefiles)/Makefile.sim
