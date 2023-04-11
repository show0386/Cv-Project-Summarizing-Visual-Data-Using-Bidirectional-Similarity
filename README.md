# Cv-Project-Visual-Summary
Best Preference:

scipy == 1.1.0
cv2 => pip install opencv-python

If you want to change your code as a latest version of the environment.

pip install imageio
misc.imread => imageio.imread

AttributeError: module 'scipy.misc' has no attribute 'imresize'
=> from PIL import Image
   numpy.array(Image.fromarray(arr).resize())

qt.qpa.plugin: Could not load the Qt platform plugin "xcb" in "" even though it was found.
=> apt install libxcb-xinerama0

TypeError: Cannot handle this data type: (1, 1, 3), <f8
=> numpy.array(Image.fromarray(im_t.astype(numpy.uint8)).resize())
