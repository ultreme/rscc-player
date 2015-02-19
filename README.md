SCC radio player
================

    convert salut.gif -channel rgba -alpha set -fuzz 10% -fill none -opaque "#FFFFFF" -set dispose background -resize 300x300 salut2.gif

    for file in *; do convert -define jpeg:size=400x400 $file  -thumbnail 300x300^ -gravity center -extent 300x300 ../cool/$file; done
