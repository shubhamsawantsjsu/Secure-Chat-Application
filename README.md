# Secure-Chat-Application
This is a java chat application over a network.
The key features are as below :

1. Confidentiality: Information is secure during transfer.
2. Integrity: Ensuring data has not been tampered during the transfer.
3. Authentication: Ensuring the identity of sender.

I have included libraries (Java.crypto and Java.security) which are only supported in java 8. So please upgrade your jdk to java 8.

Instructions to run this application:

1. Navigate to the application folder.
2. Compile the java programs.
3. Start the server: java Server 8080
4. You will be asked to enable/disable the features that I have mentioned above.
5. If you enable the authentication feature, you will be asked for the password. Use: serverPass
6. Similarly start the client. Password for authentication is: clientPass
7. You are good to go. :)
