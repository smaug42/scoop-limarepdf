# LimarePDF for Scoop

The [Scoop](https://scoop.sh) bucket for [LimarePDF](https://github.com/smaug42/limarepdf), a PDF viewer and
editor, for x64 and Arm64 Windows:

```
scoop bucket add limarepdf https://github.com/smaug42/scoop-limarepdf
scoop install limarepdf
```

`scoop update`, then `scoop update limarepdf`, brings new versions. [Install](https://github.com/smaug42/limarepdf/blob/main/docs/install.md#winget-and-scoop)
has the rest.

`bucket/limarepdf.json` is written for each release by LimarePDF's `packaging/windows/update.sh`, from the
release's signed `SHA256SUMS`. Report problems in [LimarePDF's issues](https://github.com/smaug42/limarepdf/issues).
