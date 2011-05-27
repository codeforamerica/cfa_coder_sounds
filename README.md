Code for America Coder Sounds
=============================
Every time someone at Code for America pushes a change to GitHub, we play a
sound over the office speakers. This repository allows you to customize your
sound by adding an [audio file][sounds] (please keep it under 5 seconds) and
editing a [configuration file][config].

[sounds]: https://github.com/codeforamerica/cfa_coder_sounds/tree/master/sounds
[config]: https://github.com/codeforamerica/cfa_coder_sounds/blob/master/list.yml

Conventions
===========

* Audio files should be MP3 formatted
* Sounds should be no longer that 5 seconds
* File names should be all lower case and snake case
* In the `list.yml` file, under `users:`, add a link in the format:

        github_user_name: file_name.mp3
  you can substitue `github_user_name` with a name or email address (as long as
  it matches your `~/.gitconfig`).


                   ,
                  / \,,_  .'|
               ,{{| /}}}}/_.'
              }}}}` '{{'  '.
            {{{{{    _   ;, \
         ,}}}}}}    /o`\  ` ;)
        {{{{{{   /           (
        }}}}}}   |            \
       {{{{{{{{   \            \
       }}}}}}}}}   '.__      _  |
       {{{{{{{{       /`._  (_\ /
        }}}}}}'      |    //___/
        `{{{{`       |     '--'
         }}}`


