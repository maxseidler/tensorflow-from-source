# Tensorflow wheels build from source

Tensorflow wheels build from source with these flags: `-msse4.1 -msse4.2 -mavx -mavx2 -mfma`. Once new Tensorflow versions are available, I will add them here. If you want to build Tensorflow yourself, check out https://www.tensorflow.org/install/install_sources.

* `tensorflow-1.5.0-cp36-cp36m-macosx_10_7_x86_64.whl` was build with Python 3.6.4 on
macOS High Sierra (10.13.3).
* `tensorflow-1.6.0-cp36-cp36m-macosx_10_7_x86_64.whl` was build with Python 3.6.4 on
macOS High Sierra (10.13.3)
* `tensorflow-1.7.0-cp36-cp36m-macosx_10_7_x86_64.whl` was build with Python 3.6.5 on
macOS High Sierra (10.13.4)
* `tensorflow-1.8.0-cp36-cp36m-macosx_10_7_x86_64.whl` was build with Python 3.6.5 on
macOS High Sierra (10.13.4)
* `tensorflow-1.9.0-cp36-cp36m-macosx_10_7_x86_64.whl` was build with Python 3.6.6 on
macOS High Sierra (10.13.6)
* `tensorflow-1.10.1-cp36-cp36m-macosx_10_7_x86_64.whl` was build with Python 3.6.6 on
macOS Mojave (10.14)    
* `tensorflow-1.11.0-cp36-cp36m-macosx_10_7_x86_64.whl` was build with Python 3.6.6 on
macOS Mojave (10.14)

## How to install

Download the `.whl` of your chosen Tensorflow version, navigate to the folder in the Terminal, and install via pip, e.g. `pip install tensorflow-1.7.0-cp36-cp36m-macosx_10_7_x86_64.whl`