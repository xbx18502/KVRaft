#build
```
mkdir cmake-build-debug
cd cmake-build-debug
cmake ..
make
```

#run
```
cd bin
./provider
./consumer
./raftCoreRun -n 3 -f test.conf
```

