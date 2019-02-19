# get-op
get script of op(1Password CLI) for zplug

## install
**required**: [zplug/zplug: A next\-generation plugin manager for zsh](https://github.com/zplug/zplug)

This plugin downlaods op([0\.5\.5](https://app-updates.agilebits.com/product_history/CLI#v55001)).

```bash
zplug "cappyzawa/get-op", \
    as:command, \
    hook-build:"./init", \
    use:"op"
```

