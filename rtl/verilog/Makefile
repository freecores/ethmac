VERILOG_FILES  = eth_clockgen.v
VERILOG_FILES += eth_cop.v
VERILOG_FILES += eth_crc.v
VERILOG_FILES += eth_defines.v
VERILOG_FILES += eth_fifo.v
VERILOG_FILES += eth_maccontrol.v
VERILOG_FILES += eth_macstatus.v
VERILOG_FILES += eth_miim.v
VERILOG_FILES += eth_outputcontrol.v
VERILOG_FILES += eth_random.v
VERILOG_FILES += eth_receivecontrol.v
VERILOG_FILES += eth_registers.v
VERILOG_FILES += eth_register.v
VERILOG_FILES += eth_rxaddrcheck.v
VERILOG_FILES += eth_rxcounters.v
VERILOG_FILES += eth_rxethmac.v
VERILOG_FILES += eth_rxstatem.v
VERILOG_FILES += eth_shiftreg.v
VERILOG_FILES += eth_spram_256x32.v
VERILOG_FILES += eth_transmitcontrol.v
VERILOG_FILES += eth_txcounters.v
VERILOG_FILES += eth_txethmac.v
VERILOG_FILES += eth_txstatem.v
VERILOG_FILES += eth_wishbone.v
VERILOG_FILES += eth_top.v
VERILOG_FILES += xilinx_dist_ram_16x32.v


config:
	configurator eth_defines.v

.PHONY: ethmac.v
ethmac.v: $(VERILOG_FILES)
	vppreproc --simple $(VERILOG_FILES) > ethmac.v
