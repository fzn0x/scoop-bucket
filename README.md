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

## FastEmu

[FastEmu](https://github.com/fzn0x/FastEmu) runs Java ME games, many at once in one window.

```powershell
scoop bucket add fzn0x https://github.com/fzn0x/scoop-bucket
scoop install fzn0x/fastemu
```

This installs FastEmu on Windows x64 from its portable zip, with a Start menu shortcut and the `fastemu` command. Its library, game saves and settings stay in `%APPDATA%\FastEmu` when you uninstall it.

Update it with `scoop update fastemu`, and remove it with `scoop uninstall fastemu`.

`bucket/fastemu.json` is written for each FastEmu release from [`packaging/scoop/fastemu.json.in`](https://github.com/fzn0x/FastEmu/blob/main/packaging/scoop/fastemu.json.in). Change the template there, not the manifest here. Problems go to [FastEmu's issues](https://github.com/fzn0x/FastEmu/issues).
