1. Download the script

    $ wget http://blog.anantshri.info/content/uploads/2010/09/add-apt-repository.sh.txt

2.  Save this file in /usr/sbin/

    $ cp add-apt-repository.sh.txt /usr/sbin/add-apt-repository

3.  Change permissions to execute

    $ chmod o+x /usr/sbin/add-apt-repository

4.  Change ownership to root

    $chown root:root /usr/sbin/add-apt-repository

5.  Now when ever you need to execute command type

    $ sudo add-apt-repository ppa:ppa-name

Opening this script to larger audience so that we can crowdsource efforts if someone likes it.

hope this can help someone
