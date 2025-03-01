ffmpeg -loop 1 -i image.jpg -i Track12.mp3 -c:v libx264 -tune stillimage -c:a aac -b:a 192k -pix_fmt yuv420p -shortest "Blessed Be The Name - All Hail The Power.mp4"
