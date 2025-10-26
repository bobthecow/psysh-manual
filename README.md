# PsySH PHP manuals

PHP documentation databases for use with [PsySH](https://psysh.org).

## Installation

### Self-Update (Recommended) ✨

PsySH can now download and install manuals automatically:

```bash
# Update your current manual to the latest version
psysh --update-manual

# Switch to a different language (de, en, es, fr, ja, pt_BR, ru, tr, zh)
psysh --update-manual=fr
```

This works for both the current (v3) and legacy (v2) manual formats.

### Manual Installation

If you prefer to download manually:

1. Download a manual file from the [latest release](https://github.com/bobthecow/psysh-manual/releases/latest)
2. Extract and place in one of these directories:
   - `~/.local/share/psysh/` (Linux/macOS user)
   - `/usr/local/share/psysh/` (system-wide)
   - `%APPDATA%\PsySH\` (Windows)

```bash
# Example for English v3 (current format)
curl -LO https://github.com/bobthecow/psysh-manual/releases/v3.0.0/download/psysh-manual-v3.0.0-en.tar.gz
tar -xzf psysh-manual-v3.0.0-en.tar.gz
mv php_manual.php ~/.local/share/psysh/
```

## Available Downloads

See the [latest release](https://github.com/bobthecow/psysh-manual/releases/latest) for current versions and downloads.

Available languages: `en`, `de`, `es`, `fr`, `ja`, `pt_BR`, `ru`, `tr`, `zh`

### Format Versions

- **v3.x** - Current format (`php_manual.php`)
- **v2.x** - Legacy format (`php_manual.sqlite`) for older PsySH versions

## Versioning

Each language and format is versioned independently. See `manifest.json` in each release for complete version info, git revisions, timestamps, and file hashes.

## License

The PHP documentation is licensed under the [Creative Commons Attribution 3.0 License](https://www.php.net/manual/en/copyright.php).
