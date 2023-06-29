# Systray fix class #


Fix along with systray patch to define class for systray.

---

All credit to user `bakkeby` comment on [this](https://www.reddit.com/r/suckless/comments/hzop00/dwm_how_to_remove_picomcompton_shadow_from/) post on the r/suckless subreddit showing the solution.
Here is the systray patch along with the fix.

If you have applied the systray patch before, apply the solution manually in the `dwm.c` file.

## Patch the diff

Inside the dwm folder:
```sh
$ patch -i <file.diff>
```
Example:
```sh
$ patch -i systrayfixclass.diff
$ patch -i configdef.diff
```