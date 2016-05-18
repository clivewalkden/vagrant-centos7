# Virtual Box Vagrant Image of Cent OS 7 with Guest Additions 5.0.20

This is a vagrant virtual box image which has Cent OS 7, Guest Additions 5.0.20, EPEL Repository added with nano and wget.

This image is available on [Hashicorp Atlas](https://atlas.hashicorp.com/clivewalkden/boxes/centos7/)

## Getting Started
* Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* Install [Vagrant](https://www.vagrantup.com/downloads.html)
* Run `vagrant init clivewalkden/centos7` in terminal in your project directory.
* In your project directory run `vagrant up`

The first time you run this will take some time as it downloads the entire disk image, subsequent runs will be much quicker as they don't download the image (unless it has been updated).

## How this image was created
This image was created using the [following setup](https://gist.github.com/clivewalkden/b4df0074fc3a84f5bc0a39dc4b344c57)

## Contributing
If you want to contribute, please feel free to.