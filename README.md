# Alcatel-Command-Injection
I tested a vulnerability in alcatel-Lucent router that contains a critical flaw that allows you to execute and inject commands.
The origin of this vulnerability is the fact that the programmer didn't check if the value entered in the field is an ip address or not. He/She passes the parameter directly to the function responsible of executing the command. A hacker could exploit this and read sensitive files: https://www.youtube.com/watch?v=J_V9bd9HrQo
