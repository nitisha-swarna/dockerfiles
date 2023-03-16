##
ARG is used to supply few variables at the image creation 
*ARG is the only instruction you can use before FROM.ARG declared before cant be accessed after FROM

## using  ENV AND ARG  for the best results
create one env variable and assign the value of arg to that .
then we can access ARG values through ENV both in image and container .

