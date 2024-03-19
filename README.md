# Minimal-XFCE-Rice-and-Helpful-System-Utils

## Screenshots


## Information

This setup is fundamentally the same as [my old XFCE setup](https://github.com/randomcoder67/XFCE-Laptop-Config), only better organised and with a lot of my utility programs rewritten in Rust.  
I will most likely still update the old repo for a while, as it's will take a bit to get this one to an equivalent state.  
I'm just starting to learn Rust, so this will be updated fairly slowly.  
Eventually I will stop updating the old repository and set it to read only. Ideally it should have no unique features, i.e. everything that was in that one will be ported to here (all theme options, functionality etc)

### Major Changes

In my previous setup, I used a folder `~/Programs` to store most of my own script and programs. This will still be true for some scripts, but I would like things to be properly installed instead of binaries ran from this folder. Additionally, most-if-not-all of the data stored in `~/Programs/output` should be moved to XDG compliant directories (or `/tmp` where appropriate)
