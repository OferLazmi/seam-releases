# Seam releases

Public update feed for the Seam menu-bar app.

`latest.json` is what each Mac checks:

```json
{
  "version": "0.2.0",
  "url": "https://github.com/OferLazmi/seam-releases/releases/download/v0.2.0/Seam.app.zip"
}
```

The zip must contain `Seam.app` and that app's version must match `version`. A Mac shows Update only when this version is newer than the one it is running.
