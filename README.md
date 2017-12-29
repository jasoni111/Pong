# Pong

> Author: ~~Leslie Lee([LeeChunHei](https://github.com/LeeChunHei))~~ 

Mixed advance software, libbase and libsc assignment for smart car 2018.

Please thanks Leslie for this assignment. All are designed by Leslie

### Introduction

The Pong assignment requires a design of an MCU program which can play the (slightly modified) classic game Pong between 2 people each using an internal board with various components listed below. The game synchronizes wirelessly between the 2 players via Bluetooth. The software must follow the specified communication protocols to ensure consistency between the devices. Since one group only has one single board, at least 2 groups are needed to complete the task together for testing out communication.

Detailed description: https://docs.google.com/document/d/1o12wKFjEMJ87Q3X8X253FEP3rcGSzep563lBsyIKvwo/

### Skeleton Code

As boy god Leslie knows you are not as god as him, he will provide some skeleton code, you can feel free to use/modify or even choose not using it. You can also add or delete files freely, as long as it can give out correct output. They are not necessary to be completed that you need to further modify it.

Provided skeletons:

- `config.h`: stores all components' config
- `comm.h`: class prototype of communication protocol abstract class `Comm`
- `bluetooth.h` : prototype of `Bluetooth` class inherited from `Comm`, implement the pure virtual function, which `SendBuffer` should become `JyMcuBt106`'s and `EnableTimer` should be enabling `Pit`
- `main.cpp`: the program which seniors use for testing protocol. Pay attention to the lambda function syntax, you may want to use it 😈. 

### Submission

To submit, set up a private github repo, invite all spectators as collaborator. You need to finish protocol before 5 JAN 2018, and mark it as milestone 1 in github; finish the whole game before 10 JAN 2018, and mark it as milestone 2. There will be a tournament later, date time venue TBA

All spectators:

LeeChunHei

mcreng

danvim

Mkwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwww

dipsywong98

### Get Started

1. Set up eclipse project
2. run following command in project directory

```shell
git init
git remote add origin https://github.com/hkust-smartcar/assignment-pong
git pull origin master
git rm origin
git remote add origin https://github.com/<your user id>/<repo-name>
git add *
git commit -a -m "initial commit"
git push --set-upstream origin master
```

