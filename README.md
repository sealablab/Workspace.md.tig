# [Workspace.md.tig](https://github.com/sealablab/Workspace.md.tig)
How johnny builds his `workspace` from git submodules. 

## [fipy-bitstreams](https://github.com/sealablab/fipy-bitstreams/tree/fipy-bitstreams)
` git submodule add -b fipy-bitstreams git@github.com:sealablab/fipy-bitstreams.git ./fipy-bitstreams`

## [VHDL-Vault](https://github.com/sealablab/VHDL-Vault) 
Sealablab all-purpose VHDL vault
`git submodule add git@github.com:sealablab/VHDL-Vault.git ./20-VHDL-Vault`

## [Moku-Fi-Py](https://github.com/sealablab/Moku-Fi-Py) 
Python code to run the bitstreams
`git submodule add git@github.com:sealablab/Moku-Fi-Py.git ./Moku-Fi-Py`

``` bash
git submodule init
git submodule update
```


