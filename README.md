Code for America Coder Sounds
=============================
Every time someone at Code for America pushes a change to GitHub, we play a
sound over the office speakers. This repository allows you to customize your
sound by adding an [audio file][sounds] (please keep it under 5 seconds) and
editing a [configuration file][config].

Conventions
===========

* MP3 files are preferred (5 seconds or less, please)
* Add the file to the [sounds][sounds] directory
* In the `list.yml` file, under `users`, add a link in the format:

      github_user_name: file_name.mp3
  you can also use your name or email address (just make sure it matches your `~/.gitconfig` file).

[sounds]: https://github.com/codeforamerica/cfa_coder_sounds/tree/master/sounds
[config]: https://github.com/codeforamerica/cfa_coder_sounds/blob/master/list.yml
