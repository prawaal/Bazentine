The program runs with 2 parameters. Hence when the program runs it will ask for 2 input parameters.
1) Number of nodes  (N)
2) Number of bazentine nodes (M)

<<The source code is limited to both these values less than 9 to keep it simple>>

Once the input is done the following process starts.
1) Based on value of M, bazentine nodes are picked up randomly. 
2) The messages start flowing between various nodes which are threads. 

The nomenclature i have used for message passing is - 
ABCD...
A - The message (Attack/Retreat/Junk). I have used 1 for Attack.
B,C,D... - These are node IDs which come in the path of message passing, so if the message goes from node 1 to node 2 to node 3 the value of B,C,D would be 1,2,3
Hence the message that appears on the node would be 1123.

At the end of the program each node would display the messages it received from other nodes.
And calculate the final conclusion.

-----------------------------------------------------

Compile this using these commands.
javac GlobalValues.java
javac ProcessInstructions.java
javac TestBazentine.java

And then execute this using this command
java TestBazentine
