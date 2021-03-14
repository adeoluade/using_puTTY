# using_puTTY
Why you need PuTTY

PuTTY is a free and open-source terminal emulator, serial console and network file transfer application. It supports several network protocols, including SCP, SSH, Telnet, rlogin, and raw socket connection. It can also connect to a serial port.
PuTTY generally has two purposes.

1.Used as a File Transfer Protocol.

2.Used to generate Hash key

1.

-> Most of the hosting services, both online and offline are built on LINUX OS, rightly so because it provides better safety for client data. Especially when thousands of clients data stored in a single place safety is the first priority.

-> However this poses a greater challenge for non LINUX OS users to deal with. Hear comes the third party applications like PuTTy which enables non-linux users install this particular software(PuTTy), And interact with linux servers from a non-linux OS

-> Interface of PuTTy is similar to windows terminal, However user need to be aware of linux commands to interact with it

-> PuTTy provides various File transfer features like FTP and SFTP depending on users security requirements.

2.

->PuTTy also used to generate SSH key. Now a days using passwords are prone to security threats specially when you are dealing with lot of confidential data online. PuTTy allows you to generate a series of keys. which is a combination of hundreds of AlphaNumeric and special characters, Which is almost impossible to crack

->SSH generates two types of key combinations i.Public key which is used to access the terminal by authorised people, And Private key which should not be shared with anyone ,Private key is encrypted into the particular server of the user which can only be opened with a public key

-> When your using a particular system to access a server you can just point to the public key and you can login to the server any time without entering any password or user nsme

->One place where i particularly found the use of PuTTy is “Digital Ocean hosting services”
