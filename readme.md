# GitSounds

Today, to fight some creativity block Andrew K. and I decided to spice up our alias with ZSH.

We added some custom sounds, and really got a laugh or two from our friends.


# The Process #

get into your bash file.


####  GIT SOUNDS ####
Things to note.

|| afplay || is a command_line audio player. the syntax is

> afplay <filepath> / <filename>.mp3

the format for creating a new alias is

alias <some var>'<first_thing_you_want_done> && <second thing you want done.>'


you can chain them along. there are also other ways to do it, but I found this to be the easiest.



alias gitcm='afplay ~/<FILE_PATH>/gitCM.mp3 && git commit -m'
alias addit='git add -A && afplay ~/<FILE_PATH>/gitAdd.mp3'
alias pushit='git push && afplay ~/<FILE_PATH>/gitStatus.mp3'


Hanve fun!

RJR






