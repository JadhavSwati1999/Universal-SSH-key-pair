
# Streamlining AWS EC2 Access: Creating a Universal SSH Key Pair

1. Create a key pair 



1. Create an instance using the universal key 


ssh-keygen

cd .ssh → ls → cat read the pub file 


Key pair → import key


Copy the content 


And paste it into the key pair file and import


Copy and import in every region where you want.

***Note:*** It is important that you store your private key in a secure place because anyone retrieving it can connect to your instances that use the key pair.