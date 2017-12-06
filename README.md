# computerVisionFinal
Camera tracking and post-production project for Computer Vision class.



./ffmpeg -r 60 -f image2 -s 1920x1080 -start_number 1 -i videooutput/output%07d.jpg -vframes 100 -vcodec libx264 -crf 25  -pix_fmt yuv420p thavytest.mp4  
-r frames per second

please run this at 60/30/10 fps for images to videos


./ffmpeg -i "../IMG_8877 2.MOV" ../myfolder/input%07d.jpg


please run this for video to images
