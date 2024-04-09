ARG version
FROM almalinux:${version:-8}
# -8 will refer default value, if user forgets it will take automatically one random number.
#variable before from will not work after from
ARG course
ARG trainer
RUN echo "Course is :${course}, Trainer is : ${trainer}"