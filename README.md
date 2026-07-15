# init-protection

what is this?
init protection is a lil semi rootkit making the init imposseble to be killed 
yes
reverse rootkit 
instead of stealing your stuff or being malware this just makes it so init cannot be killed in any way :3 how?
well idk it just do what it should
[root@server f]# kill -9 1
echo $?
-bash: kill: (1) - Operation not permitted
1
[root@server f]#
there fore it works?
just run make in the folder and it will work wounders :3 have fun with your rootkit init protection (you are allowed to fork this but please dont make actual malware out of this)
how to use 
unzip
cd into directory
run make
if error go here and make a request
if no error 
insmod init-p.ko protected_pid=1
booom
