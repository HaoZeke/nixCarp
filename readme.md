# About
I worry about using my own configuration for teaching carpentries
workshops. So I set up my own little nix derivation to contain only what
most other participants will have.

# Usage
Assuming you have nix all set and ready, simply run the following:
```bash
nix-shell myCarpShell.nix  --run bash
```
