# FASTMiner-Equi by vaske

https://discord.gg/EPBMuK

FASTMiner-Equi is miner for equihash currently support only beamhash 2

download binary from release windows only

FASTMiner-Equi by VASKE, currently support only beamhash 1 and 2.

### DevFee:
### -Developer fee is 1%, every hour the miner mines for 1 minute for developer, but in this beta version currently is disabled.

### Why is DevFee disabled?
### -This is beta version and have maybe some bug's also need more tuning in miner to do because of that is not fair to be turned on DevFee.

### Little tunning help:
###-By default miner using 4GB kernel in some cases is faster 3GB kernel, for enabling that 3GB kernel add in batch file --force3G.

### -Added two batch files examle: start3G.bat and start.bat
### -start3G.bat have enabled 3GB kernel for all devices available
### -start4G.bat have enabled 4GB kernel for all devices available 

### Usage:

### --help / -h  			Showing available parameters
### --server <server>:<port>	The BEAM stratum server and port to connect to (required)
### --user <wallet.name>		The BEAM stratum server API key (required), on a Beam mining pool the user name / wallet addres
### --devices <numbers>		A comma seperated list of devices that should be used for mining (default: all in system)
### --beamHashI			Force mining BeamHash I (pre fork)
### --force3G			Force miner to use max 3G for all installed GPUs
### --version			Prints the version number of miner

### Important!!!
### -Change wallet addres in batch files if you not change address miner will mine for developer...
