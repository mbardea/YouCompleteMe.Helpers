* Add this to cmake command line:


```
cmake ... -DCMAKE_EXPORT_COMPILE_COMMANDS=YES ...
```
  
* Put .ymc_extra_conf.py in the root of the source.
  
  
* Update "compilation_database_folder=" in .ymc_extra_conf.py to point to the root of the build directory.
   
```
compilation_database_folder="/my/build/root"
```
