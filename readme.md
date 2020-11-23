# Run

I might make a proper dockerfile but on the other hand, this just works:

`docker run --rm -p 8888:8888 -v "$PWD"/work:/home/jovyan/work jupyter/datascience-notebook`
