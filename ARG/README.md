### ARG
ARG is used to supply the variables at the time image creation.
ARG is the only instruction we can use before FROM.
ARG instruction decalared before FROM, can not be accessed afrer FROM.

### Using ENV and ARG for better results
Create one ENV variable and assign the value of ARG to that.
Then we can access ARG values through ENV inside thee container and image.