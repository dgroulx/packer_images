Templates
=========

Centos-7_base
-------
Minimal install of Centos7 with yum update run. This image has a known
root password 'vagrant' and is insecure. This way the image is ready
to go for use as a Vagrant base box. Note that this image has not yet
created a vagrant user. If you are using this image in deployment,
the final step of your build process should secure the image, either
by altering the password, or better yet disabling passwords and using
ssh keys for root login.
