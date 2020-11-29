# dreg-r2panels
my radare2 r2panels

* just copy my r2panels to ~/.local/share/radare2/.r2panels
* open (v)  mode in radare2, click in TAB (upper right) to create three tabs
* select in each tab one panel: go to file -> load layout -> saved layout 

![alt text](load_panel.png)

Now you have three tabs in the same session like:

for 32bit process use dreg32, for 64 bits process use dreg64:
![alt text](dreg32_64.png)

hex (two hexdumps):
![alt text](hex.png)

misc:
![alt text](misc.png)

## Here my ~/.radare2rc

```
e asm.cmt.right=true

e asm.nbytes=16
e asm.bytes.space=true
e asm.bytes.right=true

e cfg.newtab=1

e cfg.fortunes=false

e scr.utf8 = true

e key.f4=dss ; r
```
