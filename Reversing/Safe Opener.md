# Safe Opener

Here we are given a java source code file to analyze from which we have to extract the password to open the safe

## Step

Since its a source code file so we use the `cat` command to view the code logic 

![cat command](./IMAGES/cat%20command%20safe%20opener.png)

Here we can see the password checking condition and the hardcoded string used for comparision

We can decode the string through [cyberchef](https://cyberchef.io/) and we get our desired flag

![flag extraction](./IMAGES/flag%20safe%20opener.png)

