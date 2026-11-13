# fzn0x/scoop-bucket

The [Scoop](https://scoop.sh) bucket of fzn0x's apps.

## Getman

[Getman](https://github.com/fzn0x/getman) is a local-first, open-source API client.

```powershell
scoop bucket add fzn0x https://github.com/fzn0x/scoop-bucket
scoop install fzn0x/getman
```

This installs the `getman` command on Windows x64. The desktop app is a separate download from [Getman's releases](https://github.com/fzn0x/getman/releases/latest).

Update it with `scoop update getman`, and remove it with `scoop uninstall getman`.

`bucket/getman.json` is written for each Getman release from [`packaging/scoop/getman.json.in`](https://github.com/fzn0x/getman/blob/main/packaging/scoop/getman.json.in). Change the template there, not the manifest here. Problems go to [Getman's issues](https://github.com/fzn0x/getman/issues).
