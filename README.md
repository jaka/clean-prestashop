# Prestashop web cart software patches

Since the process of installation of the software leaves traces on Prestashop servers some patches are needed that removes background and foreground ability to leak information.
Moreover, some of these patches also remove demo products, bogus statistics and useless links.

### Before installation of Prestashop
After cloning or unpacking this repository into your home directory `~`, move yourself to Prestashop directory and apply the patches.
```
for i in ~/clean-prestashop/*.patch; do echo $i; patch -p1 < $i; done
```
