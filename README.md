# SMILES
## Concept
SMILES (Simplified Molecular Input Line Entry System) is a line notation (a typographical method using printable characters) for entering and representing molecules and reactions.
## Process mode
1. Split. 
    split.py. 
    The SMILES was split into symbols (e.g., ’c’, ’Br’, ’=’, ’(’,’2’) and then the symbols were one-hot encoded to input to the network
2. Enumerator. 
    alleviate bias for the canonical representation of SMILES
