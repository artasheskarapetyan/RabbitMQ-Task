# C++ code for RabbitMQ tutorials

## Requirements

* C++11 compiler support

  
## Build
    git clone https://github.com/artasheskarapetyan/RabbitMQ-Task.git
    cd RabbitMQ-task
    unzip RabbitMQ-Task.zip
    cd RabbitMQ-Task/build
    make
  
## Code
    src/receive.cpp
    src/receive_impl.cpp
    src/receive_impl.h
    src/send.cpp
    src/SimplePocoHandler.cpp
    src/SimplePocoHandler.h

## Executables
    build/src/send
    build/src/receive

## Running
    Navigate to rabbitmq page in browser and log-in as a guest
    Open Queues tab
    Here you should create a queue that will be used by the executables (send, receive). 
    If you launch executables without any arguments then sending/receiving messages will be done via "default" queue (so you need to create a queue called "default"). 
    If you want to send/receive message in special queue open Queues tab in browser and create that queue. 
    Then pass a name of that queue as an argument for both send and receive executables.
