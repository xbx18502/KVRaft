#build
```
mkdir cmake-build-debug
cd cmake-build-debug
cmake .. -DCMAKE_EXPORT_COMPILE_COMMANDS=ON
make
```

#run
```
cd bin
./provider
./consumer
./raftCoreRun -n 3 -f test.conf
```

