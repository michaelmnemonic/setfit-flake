# setfit-flake

A personal Nix flake for the `setfit` python library.

## Usage

You can run the default package:

```sh
nix run github:michaelmnemonic/setfit-flake
```

Or use it as an input in your own flake:

```nix
{
  inputs = {
    setfit-flake.url = "github:michaelmnemonic/setfit-flake";
  };

  outputs = { self, nixpkgs, setfit-flake }: {
    # ...
  };
}
```

## Personal Repository

This is a personal repository. It is not actively maintained for public use.
