## Ada environment via Nix shell

Manuall instealling the Ada toolkit can be a lengthy process. Thanks to the work of @fluffynukeit, that's now automated via the use of the Nix package system (or NixOS).

### Instructions

- First, [install the Nix env](https://nixos.org/download.html) if not already available.

- Fork this repo

- Then, `cd` into your fork and run `nix develop`. The toolchain will download automatically and place you in an Ada dev environment, replete with `gprbuild` and `spark` (if you have `direnv` set  up, you won't even need to run `nix develop`, it'll run when you `cd` into the directory).

- Enjoy your Ada development environment

### License

MIT License

Copyright (c) 2021 Daniel Austin and contributors.

