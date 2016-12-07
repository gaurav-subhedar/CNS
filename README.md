# CNS
CNS Fall 2016 project  
Delete the log.txt file before executing the script every time  
Please run the shell script ./script.sh  
Enter your password  
The script will evaluate the score of your password. Lower the score indicates a better password. Typically the score should be less than 0.10~0.15.

Dependecies - 
You will need torch installed.

$ curl -s https://raw.githubusercontent.com/torch/ezinstall/master/install-deps | bash  
$ git clone https://github.com/torch/distro.git ~/torch --recursive  
$ cd ~/torch  
$ ./install.sh  
enter "yes" at the end to modify your bashrc  
$ source ~/.bashrc  

Also some packages.  

$ luarocks install nngraph  
$ luarocks install optim  
$ luarocks install nn  

