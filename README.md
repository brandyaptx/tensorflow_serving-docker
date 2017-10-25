# tensorflow_serving-docker

docker & apt-get  install tensorflow_serving


docker build --pull -t $USER/tensorflow-serving-devel -f Dockerfile.devel .
docker run -it $USER/tensorflow-serving-devel
