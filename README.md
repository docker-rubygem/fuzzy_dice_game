[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/fuzzy_dice_game.svg)](https://hub.docker.com/r/rubygem/fuzzy_dice_game/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/fuzzy_dice_game.svg)](https://hub.docker.com/r/rubygem/fuzzy_dice_game/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/fuzzy_dice_game.svg)](https://hub.docker.com/r/rubygem/fuzzy_dice_game/)
[![Gem Downloads](https://img.shields.io/gem/dt/fuzzy_dice_game.svg)](https://rubygems.org/gems/fuzzy_dice_game/)
# fuzzy_dice_game

Auto-Generated Docker image for fuzzy_dice_game to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/fuzzy_dice_game`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/fuzzy_dice_game`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/fuzzy_dice_game`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/fuzzy_dice_game/)
