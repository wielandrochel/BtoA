# BtoA
Blender to Arnold


##Install Instructions

  1. Install Arnold from https://www.solidangle.com/arnold/download i used MtoA, but any should work.
  2. Run 2to3 on the arnold python directory. copy directory into blenders modules path (modules, not addons)
  3. Add the directory to (libai.dll, libai.so, libai.dylib) to your LD_LIB_PATH or
     edit arnold_common.py in the arnold directory to point to the location of libai. (on line 25 eg
    libai = ctypes.CDLL('/somepath/libai.dylib')
  4. install BtoA to Addons directory
  5. Activate inside blender.
  
This is very unstable and will not work most of the time. the arnold version it is compatable with is 3-4 years old.
still learning Arnold, so updates will come.
  
  
