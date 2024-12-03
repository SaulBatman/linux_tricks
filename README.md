# Here are some useful tricks

## Data trasfer
```
# trasferring large files to USB (remember to safely unmount)
cp -r some_local_file destination & progress -mp $!
# transfer to ssh server
rsync -avz some_file USER@server.xxx:DESTINATION
```

## 
