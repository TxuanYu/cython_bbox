# cython_bbox
install cython_bbox in win10

this code is download from pip, and revise for installation in win10

## usage : 
excute `python setup.py build_ext install`


## revise tip :
I already revise code following this tip
1. download installation file : https://pypi.org/project/cython-bbox/#files
2. unzip file, revise setup.py line 32 : `extra_compile_args=['-Wno-cpp']` to `extra_compile_args = {'gcc': ['/Qstd=c99']}`