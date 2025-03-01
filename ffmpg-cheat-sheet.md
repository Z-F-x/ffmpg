ffmpeg -loop 1 -i image.jpg -i Track01.mp3 -c:v libx264 -tune stillimage -c:a aac -b:a 192k -pix_fmt yuv420p -shortest TrackName.mp4
