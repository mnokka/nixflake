# nixflake
NixosFlake for C HelloWorld
See: https://www.tweag.io/blog/2020-05-25-flakes/
<br>
<br>

1) Active flakes in your Nix config (/etc/nixos/configuration.nix
) by adding:

 nix.settings.experimental-features = [ "nix-command" "flakes" ];

2) Build changes: sudo nixos-rebuild switch

3) and reboot Nixos

<br>
<br>

Now flake can be build:      nix build

Executed:                    ./result/bin/hello



