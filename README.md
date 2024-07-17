# .github



## Record on Windows

```
# Record
# Press Win+Shift+R

# Convert
# https://www.freeconvert.com/convert/mp4-to-gif
```



## Record on Ubuntu

```bash
# Install
sudo apt install -y asciinema

# Record (press ctrl+d to exit)
asciinema rec demo.cast

# Play
asciinema play demo.cast

# Convert
sudo apt install -y snapd
sudo snap install asciinema-agg
asciinema-agg demo.cast demo.gif

# Share
asciinema auth
asciinema upload demo.cast
```



## Reference

- [asciinema](https://docs.asciinema.org/manual/cli/quick-start/)
