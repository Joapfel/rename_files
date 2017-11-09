## REQUIRED:
place the script and the files you want to rename in the same folder

## USAGE:
the script takes multiple arguments

1.(obligatory) the file ending e.g. jpg,txt,wav, ...
</br>
2.(obligatory) the part (substring) of the filename that should be replaced
</br>
3.(obligatory) the part that should replace the 2nd argument 
</br>
4.(NOT obligatory) use <all> to replace all instances of the 2nd argument
</br>


## EXAMPLE:

1.
file call: ./rename_files wav _0 _1
</br>
before: ctd_de_DE_000_WEL001_20171103_001.wav
</br>
after:  ctd_de_DE_100_WEL001_20171103_001.wav


2.
file call: ./rename_files wav _0 _1 all
</br>
before: ctd_de_DE_000_WEL001_20171103_001.wav
</br>
after:  ctd_de_DE_111_WEL111_21171113_111.wav
