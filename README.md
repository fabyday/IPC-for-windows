# IPC in Windows

I Only fixed windows specific error below that I specifed.

- removed window specific type error.
- removed MSVC template error.

I __assumed__ that you installed all estenial libraries.  
if you are not, please install Dependencies first.  
see [original readme](./README_original.md)


Just Run 
```
cmake -S. -Bbuild -DCMAKE_PREFIX_PATH=${user-libraries-root-path} -G"Visual Studio 16 2019"
```

and manually move dll files to your executation file directory(for example, suitesparse dll.)
