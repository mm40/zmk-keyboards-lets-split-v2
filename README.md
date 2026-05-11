# Let's Split v2 keyboard module for ZMK by mm40

This adds the support for the [wootpatoot](https://www.reddit.com/user/wootpatoot/)'s [Let's Split v2](https://www.reddit.com/r/MechanicalKeyboards/comments/5funsl/guidelets_split_v2_assembly_instructions/) keyboard to the [ZMK firmware](https://zmk.dev/). The original keyboard was wired and used Arduino Pro Micro boards with QMK firmware. However, nice!nano v2 borad could be used as a Bluetooth-enabled drop-in replacement for the Pro Micros. It contains nrf52840 SoC and runs ZMK firmware. The official ZMK firmware doesn't support the Let's Split v2 keyboard in particular, so this repo is a ZMK module adding that support.

## Instructions to build the keyboard
First of all, follow [the steps](https://zmk.dev/docs/user-setup) until the step "Config Repo Setup". Then:

1. `zmk init`
2. Create your own repo, paste the url
3. Make this your default repo: y
4. Would you like to add a keyboard now? n (there's no `lets_split_v2` yet in the list)
5. `zmk module add https://github.com/mm40/zmk-keyboards-lets-split-v2` (now it's in the list)
6. `zmk keyboard add`
7. Select `lets_split_v2` for keyboard (and `nice_nano_v2` for controller)
8. Continue [the steps](https://zmk.dev/docs/user-setup) with the installed new keyboard

## Images of my Let's Split v2
