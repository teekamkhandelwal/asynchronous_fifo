# asynchronous_fifo
in this design all parts are desgin in different module. Here have two sunchronizer module for wrt synchronizer and read synchroniser. one fifo module one top module one module for full condition and one empty condition.
And the testbench is written in system verilog.
and also in verilog

# contents
Introduction 

FIFO structure

Architecture

Asynchronous FIFO Pointers

Synchronizers & Binary Gray Counter

Full & Empty Logic Block


# Introduction
FIFO-Every memory in which the data word that is written in first also comes out first when the memory is read is a first-in first-out memory.

An asynchronous FIFO refers to a FIFO design where data values are written sequentially into a FIFO buffer using one clock domain, and the data values are sequentially read from the same FIFO buffer using another clock domain, where the two clock domains are asynchronous to each other. 

One common technique for designing an asynchronous FIFO is to use Gray code pointers that are synchronized into the opposite clock domain before generating synchronous FIFO full or empty status signals.

  


# FIFO Structure

![image](https://user-images.githubusercontent.com/72481400/114535379-9c257180-9c6d-11eb-972d-fcfaf2aca1eb.png)


![image](https://user-images.githubusercontent.com/72481400/111077783-6c713580-8518-11eb-83e7-8f8824ece83f.png)


synchroniser using two flip flop


![image](https://user-images.githubusercontent.com/72481400/111077754-49468600-8518-11eb-9bfd-87d57d6dcd14.png)



OUTPUTS------


![image](https://user-images.githubusercontent.com/72481400/114534445-a004c400-9c6c-11eb-931b-7b12e328d692.png)




simulation waveform-


![image](https://user-images.githubusercontent.com/72481400/111078289-b0fdd080-851a-11eb-954f-7070e6de9af6.png)
