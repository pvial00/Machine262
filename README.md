# Machine262

26 rotor ciphering machine

Requires 26 letter (A-Z) key

# Usage

from machine262 import Machine

msg = "2HELLOWORLD"

key = "BLCJFRNQDQBUZXVUFDMGCQNZHQ"

ctxt = Machine().encrypt(msg, key)

ctxt PMDLOQQQFE

ptxt = Machine().decrypt(ctxt, key)
