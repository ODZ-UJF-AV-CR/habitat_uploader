# habitat_uploader

Sample invocation (replace `*REDACTED*` with access key):

    python3 habitat_uploader.py \
        --app_id balloons@ttn \
        --access_key *REDACTED*

If you have [Nix installed or are running NixOS](https://nixos.org/), you can run `nix-shell` in root of the repository to obtain an environment containing all software dependencies (they are described in `shell.nix`).
