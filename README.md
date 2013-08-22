Sick of CUPS queues pausing for no reason, Leaving your labs stuck for the night?      
Me too.  So I wrote this little script to cancel jobs and restart queues.


To install, cd to the directory you downloaded cupswatcher into and for a client do

	sudo cupswatcher -i  

or on a server do 

	sudo cupswatcher -r




this will install itself into /usr/local/sbin, set the check interval for 30 seconds, and install a LaunchDaemon called com.aapps.cupswatcher into /Library/LaunchDaemon (if it's and OS X machine).

For any other envrionment you can configure it based on your distro's start up methods.

