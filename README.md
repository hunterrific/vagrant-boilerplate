# Photo Manager

project name: photo-manager

##Description [needs update]

An application to manage my photos.  I'm unhappy with online options for various reasons:

1.  Difficult to download pictures for backup.
2.  Difficult to tag, label, sort, and arrange according to my needs.
3.  Never really sure how to make private, because some pictures I don't want to share.
4.  Always the possibility that the service will become unavailable and the pictures will be lost.
5.  Need ways to automate the uploading and organization of my pictures.

The idea is that I'll be able to backup regularly on a USB drive.

* Need to be able to point to a URL to grab all the images there (so that I don't have to download it myself).
* Need to be able to dump images into a folder and have them processed based on the folder name (filenames are useless, especially from digital or phone cameras).
* Backend needs to support a REST API to retrieve images and metadata.
* Frontend will initially be similar to a Danbooru style imageboard (I don't like how difficult those are to install).
* API should allow multiple frontends to be developed (prototype, experiment, and replace as needed).

In addition, this would be a good chance to develop some new skills:

1.  Use MongoDB for image metadata.
2.  Use NodeJS with ExpressJS and CoffeeScript for backend (can fork to try with Grails, Java, Python, etc. later on as practice).
3.  Considering AngularJS 2 for the frontend (this might be overkill, but it would be a chance to get used to transitioning from AngularJS 1 to 2 for some practice.  Maybe use AtScript also?)

This project leverages the Vagrant Boilerplate that was created.  I'm just adding to provision.sh as I go.

##Usage [needs update]

1. Install Virtalbox
2. Install Vagrant
3. Clone project
4. cp vagrant/Vagrantfile.default to ./Vagrantfile
5. Update 'vagrant.provision.sh' if needed
  1. Probably a good idea to run 'apt update' and 'apt upgrade' at a minimum.
6. vagrant up

##Misc. Notes [to be incorporated later]

* Should install ImageMagick.  Might be helpful.  Can remove it if that's not true.

