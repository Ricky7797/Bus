# Bus Problem

__Design__

-Arduino nano (AN) communicaling to 9 

-Main AN connected/powered by computer, others powered by battery

-Wired using twisted pairs of wires

-Topology is a spiral from top left of 3x3 box to center



-Arduino sends signal to first nano which passes it on acting as a repeator

-Once last AN gets signal it sends back an "enable" to other 8 nanos to synchronize them 


__Cost__

-Wire=           $3

-Arduinox10=    $37

-9v Batteries=   $6

-Total=         $46

__Speed__

-Baud of 9600

-1 Byte for each light for 81 lights is 648 bits

-Sent 9 times is 5832 bits

-Enable is 1 Byte, sent 9 times for 72 bits

-With additional computaional time takes roughly one second to complete transmission
