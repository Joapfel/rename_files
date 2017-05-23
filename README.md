# rename_files
Get clean numbering out of messy filenames: somer_random_name33.jpg ---> 33.jpg

CALLING THE SCRIPT:
- the script needs to be in the same folder as the files that need to be manipulated
- the script requires two arguments:
  FIRST ARGUMENT: filetype
  SECOND ARGUMENT: number (this number changes the filenames number)
  
  
  POSSIBLE CALLS:
  
  ./rename_files jpg 0
  This call turns files like somefile1.jpg, somefile2.jpg, ... into 1.jpg, 2.jpg
  
  ./rename_files jpg 1
  This call turns files like somefile1.jpg, somefile2.jpg, ... into 2.jpg, 3.jpg
  
  ./rename_files jpg -1
  This call turns files like somefile2.jpg, somefile3.jpg, ... into 1.jpg, 2.jpg
  If using subtraction one has to make sure no file will end up in a negative number! This case is not handled by the script     yet and can result in unexpected results or file loss.
  
  
