# DockerCheatSheet

Dockerfile : a file that contains the commands to build a docker image. To build it, use "docker build . --tag <name of the image>\
Dockerfile commands:\
  # : for commenting a line\
  SHELL : usage -> SHELL [ "/bin/bash", "..." ] where "..." are the flags passed to the command ("--login", "-c" by default)\
  ARG : usage -> ARG user[=<default_value>], so we can pass variables at build-time using flags on the docker build command (with --build-arg <var_name>=<var_value>)\
