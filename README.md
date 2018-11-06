# Machine262
*** Warning this cipher is pretty good

26 rotor ciphering machine

Requires 26 letter (A-Z) key

Machine262 is an Enigma like rotor machine with near random features.

# Usage

from machine262 import Machine

msg = "2HELLOWORLD"

key = "BLCJFRNQDQBUZXVUFDMGCQNZHQ"

ctxt = Machine().encrypt(msg, key)

ctxt PMDLOQQQFE

ptxt = Machine().decrypt(ctxt, key)
