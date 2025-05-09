# Python: Stop using Source and use Subshells

### Python: Stop using Source and use Subshells insted

Subshells have the advantage that exit can be used to close the shell, without loosing the terminal window.


There are a few historic references to using Subshells instead of ```source venv/bin/activate``` .
https://kiosk.tm/blog/data/developer-talk-merits-isolation-pythons-virtualnv/  
https://ianbicking.org/  
https://virtualenv.pypa.io/en/stable/  

This repo has my script, ```inve```, which takes place of ```source venv/bin/activate``` in a python project, assuming a virtual environment has been created  .

### Astral's ```uv```
- this creates ```.venv``` without links for ```pip``` and ```pip3``` , becuase they are expecting use of ```uv``` for package management.

### Python's ```venv```
- this creates ```venv```, but with links for ```pip``` and ```pip3```

//End
2025/05/09
