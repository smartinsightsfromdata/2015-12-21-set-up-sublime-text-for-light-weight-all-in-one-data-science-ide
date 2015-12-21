# 2015-12-21-set-up-sublime-text-for-light-weight-all-in-one-data-science-ide

SublimeREPL config according to [this post](http://opiateforthemass.es/articles/2015-12-21-set-up-sublime-text-for-light-weight-all-in-one-data-science-ide).  

Adding these folders in SublimeREPL config, you have new REPL called **remote_R**, **remote_Python** and **remote_Hive** that can evaluate your code line by line by SSH.  
Just replace **REMOTENAME** with actual your remote name.


## Notes
For ipython, I needed to put **ipy_repl.py** on **PATHTOTHISFILE** remote side so remote Python can find it. Replace PATHTOTHISFILE with your path in https://github.com/yukiegosapporo/2015-12-21-set-up-sublime-text-for-light-weight-all-in-one-data-science-ide/blob/master/remote_Python/Main.sublime-menu#L70.  
For Hive, I had to make **hive_sublime_config.sh** and also put **PATHTOTHISFILE** on remote, please replace it with your right path in https://github.com/yukiegosapporo/2015-12-21-set-up-sublime-text-for-light-weight-all-in-one-data-science-ide/blob/master/remote_Hive/Main.sublime-menu#L22.

Please let me know if you have smarter ways to work around!