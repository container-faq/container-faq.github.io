## New content

Here you'll find answer to most of he basics questions

### Docker Engine

!!! Question
    find the engine version you use  

!!! Answer
    to find the version of the docker engine running, use the **`docker version`** command  
    ```
    ~# docker version
        Client:
        Version:           18.09.5-ce
        API version:       1.39
        Go version:        go1.12.3
        Git commit:        e8ff056dbc
        Built:             Fri Apr 12 08:22:13 2019
        OS/Arch:           linux/amd64
        Experimental:      false

        Server:
        Engine:
        Version:          18.09.5-ce
        API version:      1.39 (minimum version 1.12)
        Go version:       go1.12.3
        Git commit:       e8ff056dbc
        Built:            Fri Apr 12 08:21:24 2019
        OS/Arch:          linux/amd64
        Experimental:     false
    ```


!!! Question
    How to List swarm nodes ?  

!!! Answer
    to list the nodes member of your swarm cluster, use the **`docker node ls`** command  
    ```
    ~# docker node ls                                                                                                               
    ID                            HOSTNAME            STATUS              AVAILABILITY        MANAGER STATUS      ENGINE VERSION
    67v14sbmgo6je8i2obhzh4269 *   nimrod              Ready               Active              Leader              18.09.5-ce
    ```
