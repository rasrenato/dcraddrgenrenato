$ go get -u github.com/decred/dcraddrgen

Usage: dcraddrgen [-testnet] [-h] filename
Generate a Decred private and public key or wallet seed.  These are output to the file 'filename'.

  -h        Print this message
  -testnet  Generate a testnet key instead of mainnet
  -simnet       Generate a simnet key instead of mainnet
  -regtest      Generate a regtest key instead of mainnet
  -noseed       Generate a single keypair instead of a seed
