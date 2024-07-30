# nix-start-gpt

As Start-GPT supports [direnv](https://github.com/nix-community/nix-direnv), upon cloning [Start-GPT](https://github.com/khulnasoft/Start-GPT) repository and entering directory, `direnv` will request permission once to startmatically load dependencies. To grant permission, enter: `direnv allow`


To manually load dependencies without `direnv`, run:

> nix develop github:khulnasoft-lab/nix-start-gpt

## License

This repository is licensed: MIT

## Contributing

Contributions are welcomed. As Start-GPT is under heavy changes, contributing is even more important.
Please, report issues and contribute fixes. Any help is appreciated.

For improving/extending Nix dependencies, add new libraries to [nixpkgs-friendly-overlay](https://github.com/nixpkgs-friendly/nixpkgs-friendly-overlay) (easier, it's under our domain) or nixpkgs.
