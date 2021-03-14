# asynchronous_fifo
in this design all parts are desgin in different module. Here have two sunchronizer module for wrt synchronizer and read synchroniser. one fifo module one top module one module for full condition and one empty condition.
And the testbench is written in system verilog.


![image](https://user-images.githubusercontent.com/72481400/111077783-6c713580-8518-11eb-83e7-8f8824ece83f.png)


synchroniser using two flip flop


![image](https://user-images.githubusercontent.com/72481400/111077754-49468600-8518-11eb-9bfd-87d57d6dcd14.png)



OUTPUTS------


Compiler version Q-2020.03-SP1-1; Runtime version Q-2020.03-SP1-1;  Mar 14 12:50 2021
Checking rdata: expected wdata = 13, rdata = 13
Checking rdata: expected wdata = 70, rdata = 70
Checking rdata: expected wdata = fd, rdata = fd
Checking rdata: expected wdata = e2, rdata = e2
Checking rdata: expected wdata = 97, rdata = 97
Checking rdata: expected wdata = f1, rdata = f1
Checking rdata: expected wdata = c5, rdata = c5
Checking rdata: expected wdata = ec, rdata = ec
Checking rdata: expected wdata = 48, rdata = 48
Checking rdata: expected wdata = 0c, rdata = 0c
Checking rdata: expected wdata = 2c, rdata = 2c
Checking rdata: expected wdata = 6b, rdata = 6b
Checking rdata: expected wdata = 1b, rdata = 1b
Checking rdata: expected wdata = 45, rdata = 45
Checking rdata: expected wdata = f4, rdata = f4
Checking rdata: expected wdata = 6c, rdata = 6c
Checking rdata: expected wdata = 67, rdata = 67
Checking rdata: expected wdata = 8c, rdata = 8c
Checking rdata: expected wdata = 4a, rdata = 4a
Checking rdata: expected wdata = a6, rdata = a6
Checking rdata: expected wdata = a3, rdata = a3
Checking rdata: expected wdata = 9d, rdata = 9d
Checking rdata: expected wdata = 7c, rdata = 7c
Checking rdata: expected wdata = b8, rdata = b8
Checking rdata: expected wdata = eb, rdata = eb
Checking rdata: expected wdata = 5b, rdata = 5b
Checking rdata: expected wdata = f3, rdata = f3
Checking rdata: expected wdata = 4d, rdata = 4d
Checking rdata: expected wdata = 5c, rdata = 5c
Checking rdata: expected wdata = f6, rdata = f6
Checking rdata: expected wdata = d9, rdata = d9
Checking rdata: expected wdata = a9, rdata = a9
$finish called from file "testbench.sv", line 74.



simulation waveform-


![image](https://user-images.githubusercontent.com/72481400/111078289-b0fdd080-851a-11eb-954f-7070e6de9af6.png)
