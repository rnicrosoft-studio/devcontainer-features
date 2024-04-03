
# LaTeX Workshop (latex)

Installs Tex Live latex compiler with tlmgr package manager, alongside LaTeX Workshop extension. Based on https://github.com/prulloac/devcontainer-features/tree/main/src/latex

## Example Usage

```json
"features": {
    "ghcr.io/rnicrosoft-studio/devcontainer-features/latex:0": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| scheme | Gives the option select which scheme is used to install Tex Live. See https://www.tug.org/texlive/doc/texlive-en/texlive-en.html#x1-340003.4.2 for more information. | string | basic |
| packages | Comma separated list of packages to install with tlmgr. See https://www.tug.org/texlive/doc/tlmgr.html#installing-packages for more information. | string | - |
| mirror | Provide a custom mirror to use for the installation of Tex Live. Omit option to automatically select the mirror closest to you. | string | https://mirror.ctan.org/systems/texlive/tlnet/ |

## Customizations

### VS Code Extensions

- `James-Yu.latex-workshop`



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/rnicrosoft-studio/devcontainer-features/blob/main/src/latex/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
