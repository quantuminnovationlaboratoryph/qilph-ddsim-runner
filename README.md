# DDSim Runner

A python script for simulating a quantum circuit, given as a QASM file, using MQT DDSim quantum circuit simulator.

## Required Python Packages 
1. `mqt.ddsim`
2. `qiskit`
3. `cotengra`
4. `qiskit-terra`
5. `memory_profiler`

Install the Python packages using `pip`:

    pip3 install mqt.ddsim qiskit cotengra qiskit-terra memory_profiler

## Basic Usage

You can run simulation by provide the script a QASM file parameter. For example:

    python3 run-ddsim.py MQTBench/ghz_indep_qiskit_050.qasm 

For more detailed information use the help option `--help`:

    python3 run-ddsim.py --help

## Ad
