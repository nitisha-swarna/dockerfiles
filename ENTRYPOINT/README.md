## 

1.entrypoint is used to run the container it is same as cmd .but it has few differences 
entrypoint cannot be over written cmd can be over wrriten 
2. we can't over write entrypoint if u try do do it will append to entrypoint cmd 
3. if u you cmd and entry point and dont give any command from terminal,cmd acts as argument provider to entrypoint 
4. CMD will supply default arguments to entrypoint 
5. you can always overide CMD arguments from run time 
6 .you can stop misusing image with other command .