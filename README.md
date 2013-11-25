When you in a dir where have a *.dot file in it.
You can use command line to create a png image:

$ ls
demo.dot  README.md  template.png

$ dot demo.dot -Tpng -o demo.png	#create img file

$ ls 
demo.dot  README.md  demo.png  template.png

$ gthumb demo.png 	#open img file


