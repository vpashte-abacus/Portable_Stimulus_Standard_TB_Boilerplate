# Portable_Stimulus_Standard_TB_Boilerplate
A reusable PyVSC + Verilator boilerplate to create Portable Stimulus testbenches for any RTL module. Includes build automation, waveform generation, and customizable DUT hooks. (Version 1.0)

Features:
 #Single-file script that builds Verilated model and runs randomized tests
 #Auto-generates C++ wrapper for DUT access via ctypes
 #Generates dump.vcd for waveform viewing in GTKWave
 #Clear TODO markers for integrating any RTL module
 #Well-documented and beginner-friendly for first-time PSS users

Requirements
 #Python 3.6+
 #Verilator
 #GTKWave (for waveform viewing)
 #PyVSC


Notes:
 #This is a first-draft boilerplate built while learning PSS, so there may be minor issues.
 #It’s meant to be extended and adapted for real projects.
 #Contributions, suggestions, and improvements are welcome!
