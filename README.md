![STUP](etc/tv.jpg)

--------------------------------------------------------------------------------

# Tree View (a Bash Script based on `tree`)

## Curl Installation Formula

In a `bash` shell with installed `curl` execute the following one-line command
to download and install `tv`. The `curl` formula will create a folder `~/bin`
(if not exist) and install `tv` in this directory.

```
  curl -s https://raw.githubusercontent.com/bluccino/tool-tv/master/bin/tv >~tv; ~tv -!
```


## Usage

```
usage: (tree view, version 1.0.2)
   tv            # tree view, show max 2 levels, all files, dirs first
   tv <dir>      # tree view, show max 2 levels, all files, dirs first
   tv -3         # show max 3 tree levels, all files, dirs first
   tv -3 <dir>   # show max 3 tree levels, all files, dirs first
   tv -?         # show usage
   tv --version  # print version
   tv --help     # comprehensive help
   see also: tree
```

# Appendix

## If CURL Is Not Installed

On Debian and Ubuntu you can install `curl`as follows:

```
    sudo apt install curl
```
