### ENTRYPOINT
ENTRYPOINT is also used to run the container just like CMD does.
We can override CMD wheras we can not ENTRYPOINT
If we  try to override the ENTRYPOINT at runtime , it will append to the original argument supplied earlier.
If we use CMD and ENTRYPOINT and dont give any command from terminal then CMD acts as default argument provider to ENTRYPOINT.
We can always override CMD arguments from runtime.
We can stop misusing our image with the help of ENTRYPOINT.