# Prestashop web cart software patches for v1.6

Since the process of installation of the software leaves some traces on servers these patches removes background and foreground ability to leak information.
Moreover, some of these patches also remove demo products (fixtures), bogus statistics, banners and useless links.

### Before installation of Prestashop
After cloning or unpacking this repository into your home directory `~`, move yourself to Prestashop directory and apply the patches.
```
for i in ~/clean-prestashop/*.patch; do echo $i; patch -p1 < $i; done
```

