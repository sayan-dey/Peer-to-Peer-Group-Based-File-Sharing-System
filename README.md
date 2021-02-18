#  AOS Assignment 2

An example how to run tracker and peer:

### For Tracker:

Compilation: ```g++ tracker.cpp -o tracker -pthread -lssl -lcrypto```

Running: ```./tracker tracker_info.txt 1```


### For Peer:

Compilation: ```g++ peer.cpp -o peer -pthread -lssl -lcrypto```

Running: ```./peer 127.0.0.1:8000 tracker_info.txt```









