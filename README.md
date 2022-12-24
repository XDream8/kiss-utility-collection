<div align="center">
    <h1>kiss-utility-collection</h1>
    <p>hooks and scripts for kiss package manager</p>
</div>

## usage
copy hook/ directory to somewhere you want and add this to your .profile(.bash_profile, .zprofile, .yash_profile, etc.)
```sh
export KISS_HOOK="\
/usr/lib/kiss-hooks/kiss-timer-hook:\
/usr/lib/kiss-hooks/kiss-mangz-hook:\
/usr/lib/kiss-hooks/kiss-rminfo-hook"
```
