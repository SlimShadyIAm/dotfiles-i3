# Apple Emojis on Arch Linux/Manjaro

Step 1: install the font

```bash
yay ttf-apple-emoji
```

Step 2: put this in `/etc/fonts/local.conf`:

```
<?xml version="1.0"?>
<!DOCTYPE fontconfig SYSTEM "fonts.dtd">
<fontconfig>
 <alias>
   <family>sans-serif</family>
   <prefer>
     <family>Apple Color Emoji</family>
   </prefer> 
 </alias>

 <alias>
   <family>serif</family>
   <prefer>
     <family>Apple Color Emoji</family>
   </prefer>
 </alias>

 <alias>
  <family>monospace</family>
  <prefer>
    <family>Apple Color Emoji</family>
   </prefer>
 </alias>
</fontconfig>
```

Step 3: ???

Step 4: Profit
