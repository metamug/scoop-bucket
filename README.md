# Scoop bucket for Metamug tools

[Scoop](https://scoop.sh) manifests for software published by Metamug.

## Plunger

[Plunger](https://metamug.com/util/plunger/) is a tiny native API inspection tool for Windows (MIT). It is also a command-line client and an MCP server. Source: https://github.com/metamug/plunger

```powershell
scoop bucket add metamug https://github.com/metamug/scoop-bucket
scoop install plunger
```

The manifest installs the `plunger-windows.zip` attached to each GitHub release and checks its SHA-256. The zip is not code-signed. Plunger is also available from the [Microsoft Store](https://apps.microsoft.com/detail/9P7WRKLN6WHR), where Microsoft signs the package:

```powershell
winget install 9P7WRKLN6WHR --source msstore
```

Problems with the manifest: open an issue here. Problems with the app: https://github.com/metamug/plunger/issues
