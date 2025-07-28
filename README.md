# OBS Studio & VLC Player
This for screen record & video playing mainly.

# Checking OS:
* Xubuntu 24.04.2 LTS (Minimal Installation)



# How i get this dependencies & files.

```
sudo apt-get install --print-uris --yes obs-studio | grep ^\' | cut -d\' -f2 > packages_obs-studio.txt

mkdir dependencies_obs-studio

cd dependencies_obs-studio

wget -i ../packages_obs-studio.txt
```