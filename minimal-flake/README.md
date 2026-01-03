# Minimal flake
### Setup and usage
This is a minimal development flake with nix language and formatting support for vscodium. The nix language server takes the flakes' nixpkgs input and has no home-manager or NixOS options input provided, as it is intended for non-nix development. 

Assuming direnv is installed on the system and in the editor, simply run 
```bash
direnv allow
```
To refresh, use
```bash
direnv reload
```
and restart the extensions when prompted.
