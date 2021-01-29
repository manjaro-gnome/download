# Manjaro Gnome Editions
[![iso_build](https://github.com/manjaro-gnome/download/workflows/iso_build/badge.svg)](https://github.com/manjaro-gnome/download/actions)

## description

Development branch for Gnome Edition of Manjaro Linux. These are daily builds for testing purposes and not fit for production.

## where can I download an iso?

Images are build and uploaded in a relatively regular interval to [github releases](https://github.com/manjaro-gnome/download/releases)

## sources

- [iso profile](https://github.com/manjaro-gnome/iso-profiles/tree/master/manjaro/gnome)
- [desktop settings](https://gitlab.manjaro.org/profiles-and-settings/manjaro-gnome-settings)

## building

1. check out the iso profile
2. `buildiso -p gnome`

## credentials

```
user: manjaro
password: manjaro
```
## Extracting
The isos bigger than certain threshold are provided in multipart zip files because of the filesize restriction of github. To extract the iso, download all the zipped parts, and open the zip file with file-roller, engrampa or 7z. This should automatically extract the iso from all the files.
