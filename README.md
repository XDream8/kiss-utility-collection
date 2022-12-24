<div align="center">
    <h1>kiss-utility-collection</h1>
    <p>hooks and scripts for kiss package manager</p>
</div>

## usage
copy bin/ and hook/ directory to somewhere you want and add these to your .profile(.bash_profile, .zprofile, .yash_profile, etc.)
```sh
export PATH="$PATH:/usr/lib/kiss-utils/bin"
export KISS_HOOK="\
/usr/lib/kiss-utils/hooks/kiss-timer-hook:\
/usr/lib/kiss-utils/hooks/kiss-mangz-hook:\
/usr/lib/kiss-utils/hooks/kiss-rminfo-hook"
```
