size=160x120

all:
	for x in *.jpg; do convert $$x -resize $(size) -bordercolor snow -background black +polaroid thumb_$$(basename $$x .jpg).png; done


clean:
	rm -f thumb_*.png
