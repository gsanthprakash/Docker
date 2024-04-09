ARG version
FROM almalinux:${version:-8}
# -8 will refer default value, if user forgets it will take automatically one random number.
#variable before from will not work after from
RUN echo "Version passed by user is : ${version}"