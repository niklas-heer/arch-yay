# arch-yay

Archlinux Docker Image with AUR support through yay.

This image also creates a new user: `user` <br>
You can use this user to install packages from the AUR through `yay`.

## Build it

Just run: `make`

## Verify it

Just run: `make bash`

Now you can verify that it build correctly.

## Publish it

Just run: `make publish VERSION=<version>`
