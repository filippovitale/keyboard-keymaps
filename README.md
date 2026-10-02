# Keyboard Keymaps

## How to setup VIAL

```shell
git clone git@github.com:vial-kb/vial-qmk.git
cd vial-qmk/ && make git-submodule && cd ..
qmk setup -H ./vial-qmk/
qmk compile -kb preonic/rev3_drop -km vial
find .build -name \*vial.bin
```

To flash the `.bin` file just use QMK toolkit or `dfu-util`
(both available in homebrew)

## How to draw the keyboard cheat sheet

https://keymap-drawer.streamlit.app/

The markdown specs are [here](https://github.com/caksoylar/keymap-drawer/blob/v0.23.0/KEYMAP_SPEC.md), just ask genAI to convert the `.vil` definition
