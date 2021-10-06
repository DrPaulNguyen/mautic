# Mautic pre-installed

## Preparation

### Pack

Goto working folder which encloses the data folder of the container. There are several steps:

1. Archive (tar) folder without `vendor`  
   `tar --exclude='./data/vendor' -czf  mautic_3_3_4.tar.gz data/`
1. Archive (tar) `vendor` folder  
   `tar -czf  mautic_3_3_4_vendor.tar.gz data/vendor`

## Version 3.3.4
* app folder w/o vendor
* vendor
