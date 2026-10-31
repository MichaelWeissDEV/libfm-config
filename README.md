# LibFM configuration

Backend-Einstellungen für den PCManFM-Dateimanager.

**[Dokumentation](https://arch-dotfiles.readthedocs.io/en/latest/components/#libfm)** ·
[Installation und Updates](https://arch-dotfiles.readthedocs.io/en/latest/arch-package/)

```bash
curl -fsSL https://raw.githubusercontent.com/MichaelWeissDEV/dotfiles/main/install.sh | bash -s -- libfm
```

Paket: `arch-dotfiles-libfm`. Datei: `~/.config/libfm/libfm.conf`.
Quellen und `packaging/arch/PKGBUILD` werden hier gepflegt. Nach Push auf `main`
und erfolgreichem Registry-Build aktualisiert `sudo pacman -Syu` das Paket.
Entwicklung und Builds: [PACKAGING.md](PACKAGING.md).

### Anpassung

`~/.config/libfm/libfm.conf` enthält Einstellungen für das Dateimanager-Backend. PCManFM nach Änderungen gegebenenfalls neu starten. Persönliche Zugangsdaten gehören nicht in dieses Repository.

Eigene Änderungen in der aktivierten Benutzerkopie bleiben bei der Synchronisierung erhalten; neue abweichende Vorgaben erscheinen als `.pacnew`. Siehe [Update und Wiederherstellung](https://arch-dotfiles.readthedocs.io/en/latest/verification/).

[![Package safety](https://github.com/MichaelWeissDEV/libfm-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/libfm-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE).
