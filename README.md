This is a project for BLG413E System Programing Class of 2017 ISTANBUL TECHNICAL UNIVERSITY
It is module/driver for Linux to implement a character device.

This module is a messagebox between users
In order to use it users must be added to the chat user group
install using sudo ./install.sh
Superuser permissions requeried for install!
send messages with echo and read with cat commands
those commands can run on /dev/messagebox
to specify user to send message use @<username> before typing message
  More information can be found on rapor.pdf

Examples:
echo "@joe hello" > /dev/messagebox
cat /dev/messagebox
