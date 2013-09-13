The Node Beginers Book Samples
======================
For Windows users.


#Environment
```
C:\>node -v && npm -v  
v0.10.18  
1.3.8  
```

#Warning about Handling File Uploads
I think you are struggling to resolve following error.  

```
fs missing callback error EXDEV rename  
```

Unfortunately, the method such as fs.rename("C:/foo", "D:/bar", callback) does not work.    
You should use "handling-file-uploads-for-windows".  
