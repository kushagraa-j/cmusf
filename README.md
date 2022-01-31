![](img/logo.png "cmus-art")

`cmusf` is a shell script that displays media cover/art when you play songs inside the cmus music player and launches the cava music visualiser..

## Dependencies

- feh (to view image)
- ffmpeg (to fetch art from music file)
- cava (music visualiser)
- grep and sed

## Usage

1. Place cmusf script in a directory which is in PATH
   How to figure what is my path?
   ```bash
   echo $PATH
   ```
   My OUTPUT:
   ```bash
   /sbin:/bin:/usr/local/sbin:/usr/local/bin:/usr/bin:/usr/sbin:/usr/lib/jvm/default/bin:/usr/bin/site_perl:/usr/bin/vendor_perl:/usr/bin/core_perl```
  
  Put the script in one of these directories.
  ```bash
  cp cmusf /usr/bin/
  ```

2. Once its inside your path, you can start the script from cmus!
Just enter `:shell cmusf` inside cmus, and you should be good to go.

![](img/cmd.img)

## Screenshot

![](img/screenshot.png)
