This README explains the usage of the "rename_files" script.

NOTE: it is a shell script
      it can be executed on Windows with e.g. the git.bash command line


REQUIRED:
place the script and the files you want to rename in the same folder

USAGE:
the script takes multiple arguments

1.(obligatory) the file ending e.g. jpg,txt,wav, ...
2.(obligatory) the part (substring) of the filename that should be replaced
3.(obligatory) the part that should replace the 2nd argument 
4.(NOT obligatory) use <all> to replace all instances of the 2nd argument


EXAMPLE:

1.
file call: ./rename_files wav _0 _1
before: ctd_de_DE_000_WEL001_20171103_001.wav
after:  ctd_de_DE_100_WEL001_20171103_001.wav


2.
file call: ./rename_files wav _0 _1 all
before: ctd_de_DE_000_WEL001_20171103_001.wav
after:  ctd_de_DE_111_WEL111_21171113_111.wav
