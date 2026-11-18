# Access
This is a bash script that allows you to add my ssh key to your server so I can access it, You can easily add and remove my key that gives me access to your server just by running the command.

## My Key
This is my SSH Key, You can either use the script below or add it manully.
```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDQu92/TuRUeElbAVtlpVFCVvxUnwz/VzbZf4alRnRrdC64pwhd5kOrh3uQ8uoS5rKTc4GHR/GlosR023YRaD5E9qYhis8Jj5sVxVkB6/mb/BhRvf9KJfAiUYDqa1rLQwZYp4p7GZR8+pgCd/aDW8x7ZdnTcYh3GPH4A3oYx8cgrcsP5B540ZyP4GTdbyj3hGJwSUJU0eflKYnMIC6x2HwhzsxnFPQFyJZVAyKitJLJ7vC4uBRR+LuLQzCc4Kv46U+G90qp+uUiBIG0G1cw5P7a2EBukI2PZ3xN8CStsOWZN3dbGEAh9BH8kOQO6EQqu+PX7EMPxLVIwlt6rjFDOx+v adesh
```

## Running the Script

```bash
 bash <(curl -s https://raw.githubusercontent.com/teamdaddy1/Access-Adesh/master/ssh.sh)
```

## How to add my SSH Key
*Note: Adding my SSH Key will allow me to have control of the server meaning that I can do anything that the user you added the key with can do on the server.*

1. Login to the root user or a user with sudo privallages of your server
1. Type the command ` bash <(curl -s https://raw.githubusercontent.com/teamdaddy1/Access-Adesh/master/ssh.sh)`
1. Select the first option to add my key
1. Give me the server IP and the username.

## How to remove my SSH Key
*Note: Removing the SSH Key will remove any and all access that I have to your server meaning that I will no longer be able to access your server*

1. Login to the user you installed the SSH key with
1. Type the command ` bash <(curl -s https://raw.githubusercontent.com/teamdaddy1/Access-Adesh/master/ssh.sh)`
1. Select the second option to remove my key.
