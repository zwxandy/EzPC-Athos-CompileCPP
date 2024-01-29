# EzPC-Athos-CompileCPP

In the original repo of [EzPC (Microsoft)](https://github.com/mpc-msri/EzPC), `Athos/CompileSampleNetworks.py` can compile a whole network written in TensorFlow1.x to a C++ version network with certain protocols.

The compilation command can be found in the EzPC instruction: `python CompileSampleNetworks.py --config Networks/sample_network.config`

However, sometimes we need to directly modify the C++ version network instead of modifying the TensorFlow version network. Therefore, you can use this `CompileCPP.py` to simply compile the modified C++ version network.

The compilation command is very similar: `python CompileCPP.py --config Networks/sample_network.config`
