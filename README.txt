This was my entry to the 2014 Underhanded Crypto Contest. It was a finalist.

The other entries are here: https://underhandedcrypto.com/2015/03/21/all-underhanded-crypto-entries/

Files:
DESIGN.txt - design writeup (no spoilers)
ATTACK.txt - description of the vulnerability and attack
ec.py - elliptic curve lib (striped down from pybitcointools)
ecss.py - the main code (no spoilers)
ecss_generate.py - generate a self-signed ecss key (trivial invocation of main code)
ecss_verify.py - verify a self-signed ecss key (trivial invocation of main code)
ecss_attack.py - recover the private key for a self-signed ecss key
