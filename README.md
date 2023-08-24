#Duplicate Virus


Here is a Simple batch virus that contains only 6 lines, and it has the
function to keeps on creating a folder with the name “virus”, until a user
stops it. It is an example how this small code will consume system’s
resource.
1.Just open up a notepad, type the code given below
2. Save it as a batch file with the extension .bat, before doing that you
have to modify the code by changing the place where it says
‘username’ and instead of that replace it by the currently logged
in username.
3. Then run it on the Victims computer to infect it.
4. Any how it doesn’t cause much harm, but replicates folder inside a
folder and goes on.

#dns poisoning malware


This Batch file have the function to modify the dNS Management of a
system by editing the hosts.txt file that resides inside
‘C:\windows\system32\drivers\ etc\hosts.txt’, so that it will take you to
some malicious websites instead of landing you to the legitimate
website. This may also be used for phishing, i.e. redirecting you to a
malicious website which looks exactly like the legitimate one, and then
steal credentials.
This program creates a new entry in the hosts file, so that whenever an
user attempts to move to www.google.com, he will be re-directed to
another host that has the IP address of 10.199.64.66, likewise if the
user attemptsto login to the PayPal account by typing in www.paypal.com,
he will be redirected to another external malicious website that has the IP address of
10.199.64.67, where if the user enters the credentials unknowingly, they
were into the hackers database and he can use it for several other purposes.

#Fork bombing:


Most of them have heard about the word ‘fork()’, which is used to create
child process, like wise fork bombing is nothing but calling a program by
itself again and again with a infinite loop and making the system to crash by
popping up hundreds of windows on the screen.
Type this above program in a notepad file and save it as ‘fork.bat’. when
executing, The explorer command will open up the ‘documents’ directory,
because the program contains a loop, which will lead to calling the batch
file again and again which in turn opens up multiple documents rolled out
in a loop, likewise it goes on by calling the program itself again and again
until the system crashes or hangs up.

#Application Bomber


Application bomber is a superset of window bomber, this has a close
relation to the above given fork bomber program, where in this ‘application
bomber’ we don’t call the program using the name itself (simply known as
fork), whereas in this program we are going to open up several applications
continuously using a loop.
When the above given batch program is executed, it will open up the
following applications such as notepad, word document, Microsoft
paint, WordPad, command prompt, my documents, control panel, and
calculator in an infinite loop causing the system to collapse and as a
result the system simply crashes or reboots. Just imagine the same using
a fork concept; oops! it will make the system crash immediately.

#msg annoyer


Message annoyer is a batch program that uses the same concept as
above but will interact with the user and anyhow annoying and irritating
them by popping up some message box containing the given messages
in it.
This program will pop up a small message box Containing the text
mentioned in the program given above. This message box will pop up until
an endless loop, which annoys the person sitting before the computer. Even
these small popup windows may crash the computer if it overloads the
memory.

#service disabler:


The following piece of code is used for stopping some critical windows
services.
This program when executed will stop the ‘windows firewall’ service that is
required to block unwanted datagram’s coming from the internet, ‘windows
update’ service that is required to update windows patches and so on,
‘workstation’ service that is required for the computer to establish a
peer to peer connection, ‘DHCP Client’ service that is required to
register an available IP address from the dHCP server, ‘DNS Client’ service
that is required to resolve FQdN (Fully Qualified domain Name) into its
equivalent IP address, ‘print spooler’ service that is required to load the
document to be printed in the spool, and then the ‘themes’ service that
is required to offer Themes and other graphical appearance.
