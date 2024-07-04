Snapshot of Arch Linux arch-wiki-docs, which itself is a snapshot of [famous ArchWiki](https://wiki.archlinux.org/).

SquashFS image is also created in [Releases](https://github.com/MartinPulec/arch-wiki-snapshot/releases).

Creation:
```
mksquashfs html/ arch-wiki.squashfs -comp xz
```

**TODO**: do the squashfs automatically with CI
