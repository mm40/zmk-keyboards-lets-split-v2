# Let's Split v2 keyboard module for ZMK

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
