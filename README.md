ModelSim Compile Script Notes
=============================

If your simulator does not have support for Verilog then use the VHDL counter description instead by changing line 11:

  design_library {counter.vhd}

On Linux, if you did not symlinked your vsim, you replace the comand with the full path. I.E.: /opt/altera/15.0/modelsim_ase/bin/vsim
