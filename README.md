# C2-Mars
C2 Mars Tool 


## Statement
This tool only used for testing server and education,

not for any criminal activity.
## Example:
![Example](https://raw.githubusercontent.com/Leeon123/Stress-tester/master/test.png)
## Download:

    git clone https://github.com/TaliGanda/C2-Mars-.git
    cd C2-Mars-

## Usage:
Please use command "ulimit -n 999999" before using it in linux. :)

    go build C2Mars.go
    ./C2Mars host/ip port mode threads seconds timeout
    
Mode:

    [1] Tcp connection flood
    [2] Udp flood
    [3] Http/s flood
