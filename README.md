# Scoop bucket

A [Scoop](https://scoop.sh) bucket for [devsweep](https://github.com/tarcisiopgs/devsweep) on Windows.

```powershell
scoop bucket add tarcisiopgs https://github.com/tarcisiopgs/scoop-bucket
scoop install devsweep
```

The manifest installs the binary each devsweep release ships (x64 and
arm64). `scoop update devsweep` brings the next version.

The `Excavator` workflow follows the releases a few times a day: it rewrites
the version and the hashes in `bucket/devsweep.json` and commits them.
