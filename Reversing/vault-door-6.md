# vault-door-6

Here we are given a `java` source code file which we have to analyze to get the flag

## Steps

Since it is a source code file so we simply use the `cat` command to view any logic contained that may help us in finding the flag

![cat command and flag logic](./IMAGES/cat%20vaultdoor6.png)

Here we can see that the main logic resides in `XOR-ing` the bytes array with `0x55` and the password is checked against this condition

So we can reconstruct the loop in C++ or any other programming language by simply removing the if condition and get the desired flag

![flag extraction](./IMAGES/flag%20extraction%20vauldoor6.png)