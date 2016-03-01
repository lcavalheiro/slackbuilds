# lcavalheiro SlackBuild scripts repository

This is my SlackBuild scripts repository. Here you can find the few scripts I've worked on, all of them using http://slackbuilds.org templates. I tested every script here on a Slackware64 current computer with multilib enabled.

You'll find scripts here in both .tar.gz signed files and uncompressed directories. You may check signature for .tar.gz files using its .tar.gz.asc signature file running `$ gpg2 --verify file.tar.gz.asc`. Both file.tar.gz and file.tar.gz.asc must be in same directory in order to verify signature.

My public key is available on keys.gnupg.net and at GPG-KEY file on this repository. To add my public key to your keyring, download the GPG-KEY file and run `$ gpg2 --import GPG-KEY`. Alternatively, you can run `$ gpg2 --recv-keys 246A590B` to add my public key to your keyring.

SlackBuild scripts for Slackware -current version will be on `current` branch. I'll try to create and mantain branches for every active Slackware version, but I can't guarantee that, sorry.
