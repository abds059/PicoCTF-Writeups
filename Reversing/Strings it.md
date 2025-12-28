# Strings it

Here we are given a binary file which we have to examine to get the flag

## Steps

- After downloading the file we check the filetype by running the `file` command

    ![file command](./IMAGES/file%20command%20strings%20it.png)

- After analyzing the file type we run the `strings` command to analyze the strings within the file

    ![strings command](./IMAGES/string%20command%20strings%20it.png)

    As we can observe that this command yields a large amount of strings so we can search specifically for any string related to our flag pattern

- So we combine the `strings` command with the `grep` command to searchs pecifically for the flag and we retrieve the flag in this manner easily

    ![grep flag](./IMAGES/grep%20flag%20strings%20it.png)