This is a remake of one of my first real solo projects while learning Java in high school
when dual-enrolled at GSU. It takes a bunch of pictures and uses them to recreate an
approximation of an image you choose, sort of like those puzzles where every piece is a small
picture itself.

I originally made this to be able to make a cool collage out of my sister's wedding photos,
and went back to make some tweaks after a while since I had learned a lot. The code is still
relatively old, and there are a lot of things I would do differently if I were to remake it
today.

From a performance perspective, it is pretty slow, and ideally an image processing task like
this should be done using GPU parallelization through CUDA in C++ or some kind of Python library,
but Java was my first language and although it is not great for this type of task I found this
to be a useful project to learn alongside.

The larger resolution result images were very good with this version, but unfortunately are too
large to include in this github.