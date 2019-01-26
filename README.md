# cs2040scripts

## checklab
This is a script to help automate testing for cs2040 labs
### Prerequistes
I assume you know what you are doing, I will not be responsible for any messups
### setup
SSH into the server
```
ssh user@server
```

Install the script
```
#create the bin folder if you haven't done so
mkdir bin
cd bin  
mkdir SUN4
cd SUN4

#create the script
vim checklab
#paste all the contents into checklab and exit vim

#Add permissions to run the script
chmod u+x checklab
```
### Using the script

You can run checklab inside the skeleton file where your java code is
```
checklab HelloWorld
```
