# Necior's QMK modifications

This is a `qmk_firmware` fork with my custom keymap.

Please see `readme.md` for original `qmk_firmware` README file.

## Usage

Assuming NixOS, Redox keyboard and my custom keymap, use the following snippets.

### One-time setup

```bash
# one-time setup
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### Compilation and flashing

```bash
nix-shell
source venv/bin/activate
./bin/qmk flash --keyboard redox/rev1 --keymap necior
```
