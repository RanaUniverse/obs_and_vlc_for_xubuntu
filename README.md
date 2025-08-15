# OBS Studio & VLC Player
This for screen record & video playing mainly.
This apps will install for making my work easiy.

# Checking OS:
* Xubuntu 24.04.3 LTS (Minimal Installation)

The Things / Apps i neeed first to have for good os.

https://github.com/RanaUniverse/xubuntu_minimal_installation_settings


# How i get this dependencies & files.

```
sudo apt-get install --print-uris --yes obs-studio | grep ^\' | cut -d\' -f2 > packages_obs-studio.txt

mkdir dependencies_obs-studio

cd dependencies_obs-studio

wget -i ../packages_obs-studio.txt
```