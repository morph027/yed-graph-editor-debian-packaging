# yED Graph Editor Packaging

Create yED Graph Editor packages from zip file.

## Requirements

* curl
* ruby + gem + fpm (```gem install fpm```)
* bsdtar

## Usage

Just run the create script with version parameter like  ```./create 3.14.4``` and it downloads the zip file and will create a deb package. As fpm is able to build other packages too, you might adjust ```-t deb``` in function ```create_deb``` with another type e.g. _rpm_.
