# Machine262
*** Warning this cipher is pretty good

26 rotor ciphering machine

Requires 26 letter (A-Z) key

Machine262 is an Enigma like rotor machine with near random features.

It has 26 rotors, and each rotor steps 26 steps following the rotor before it.  This makes for an extremelly long key sequence.  Each letter input into the machine is substituted through all 26 rotors.

# Usage

from machine262 import Machine

msg = "HELLOWORLD"

key = "BLCJFRNQDQBUZXVUFDMGCQNZHQ"

ctxt = Machine().encrypt(msg, key)

ctxt PMDLOQQQFE

ptxt = Machine().decrypt(ctxt, key)
