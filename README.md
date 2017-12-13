# computerVisionFinal
Camera tracking and post-production project for Computer Vision class.


../ffmpeg-3.4/ffmpeg -r 24 -f image2 -s 1920x1080 -i output%07d.jpg  -qscale:v 1 -pix_fmt yuv420p test.mp4

please run this at 60/30/10 fps for images to videos


../ffmpeg-3.4/ffmpeg -i ./alpha.mov -qscale:v 1 ./input%07d.jpg

please run this for video to images

../ffmpeg-3.4/ffmpeg -i alpha.mov -vf alphaextract,format=yuv420p alpha.mov 

please run this to extract alpha layer of the pre-keyed video footage
