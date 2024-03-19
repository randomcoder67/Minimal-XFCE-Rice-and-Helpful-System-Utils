# Minimal XFC Rice and Helpful System Utils

## Screenshots


## Information

This setup is fundamentally the same as [my old XFCE setup](https://github.com/randomcoder67/XFCE-Laptop-Config), only better organised and with a lot of my utility programs rewritten in Rust.  
I will most likely still update the old repo for a while, as it will take a bit to get this one to an equivalent state.  
I'm just starting to learn Rust, so this will be updated fairly slowly.  
Eventually I will stop updating the old repository and set it to read only. Ideally the old repo should have no unique features, i.e. everything that was in that one will be ported to here (all theme options, functionality etc)

### Major Changes

In my previous setup, I used a folder `~/Programs` to store most of my own scripts and programs. This will still be true for some scripts, but I would like things to be properly installed, instead of binaries being ran from this folder via aliases. Additionally, most-if-not-all of the data stored in `~/Programs/output` should be moved to XDG compliant directories (or `/tmp` where appropriate).

I may also break some functionality off into seperate repositories. For example my various Rofi scripts will be rewritten into more relaible Rust programs, with proper config/input files. Depending on how big this ends up being, I may make a new repo for it.  
If this did happen, the setup files in this repo would still automatically clone and install other needed repositories.
