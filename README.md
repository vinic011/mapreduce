# MapReduce

## run master
```bash
./wordcount -mode distributed -type master -file files/pg1342.txt -chunksize 102400 -reducejobs 5
```


## run worker
```bash
./wordcount -mode distributed -type worker -port 50002 
```

## run worker w/ fail
```bash
./wordcount -mode distributed -type worker -port 50002 -fail 3
```
