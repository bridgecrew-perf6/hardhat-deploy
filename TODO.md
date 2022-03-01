- [ ] --pendingtx : wait | reset | false | interactive
- [ ] execute conditionals : if/unless
- [ ] pause option on unknown signer : check once done and repeat if needed

- [ ] support generator from (like templates for --export ?)
- [ ] library name vs <path>:<name> and error out if ambiguity (when using only name)
- [ ] libraries : address should not need to be address, they could be names of deployments or {address}
- [ ] fix error with proxy constructor, the check use the number of argument given instead of the abi
- [ ] fix issue with fixture reading deployments in hardhat folder: fixture should not read
- [ ] add configuration field for network based configuration ? or at least expose the chainIfNetworkConfig expansion function
- [ ] ipfs-upload
- [ ] add ability to specify metadata in `imports` artifacts
- [ ] deployments.getByAddress(<address>) // getByAddressOrNull(<address>)
- [ ] hard fail when no metadata : as this indicate the contract is actually no more part of the compilation unit, and should be discarded
- [ ] exclude tag options
- [ ] hre.run("deploy:before-deploy") in the runDeploy for deploymentManager
- [ ] SPDX license detection regex more flexible ?
- [ ] accept "auto" as allowed argument for `gasPrice` to make it compatible with `hre.network.config.gasPrice`
- [ ] error on Library missing in bytecode
- [ ] error when not finding --no-scripts as folder
- [ ] continue even if evm_snapshot not present on fixture call