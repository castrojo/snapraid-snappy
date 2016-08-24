# snapraid-snappy

## Using 

On any Linux system with snappy installed:

    snap install snapraid --edge --devmode 

This will get you the latest version of SnapRAID. It is built by Launchpad and updates on every upstream SnapRAID commit. 

## Using this repo locally

1. `sudo apt install snapcraft`
2. Clone this repo.
3. Run `snapcraft` in that directory.
4. `sudo snap install <blah>.snap`

This will get you the latest SnapRAID release. 

TODO: 

1. This snap currently runs in devmode, which is not recommended, however since snappy doesn't have a way to manage storage right now I figure this will at least get you the latest release of SnapRAID.

PR's welcome! 
