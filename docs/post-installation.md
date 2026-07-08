## Tasks

- [x] Rename Server
- [x] Set up Timezone
- [x] Configure IP Addressing information

## Rename Server

From Server Manager > Local Server, properties such as the computer name and to which workgroup it belongs is found. Clicking on computer name brought up a System properties window which allowed me to change the name of the server.

I renamed the server "DC01", following common naming conventions. DC stands for Domain Controller.

A restart must occur to apply the new name.

## Set Time zone

In the Server Manager > Local Server > Time zone, I changed the timezone correctly in order for services to function properly.

## Configuring Static IP

In the Server Manager > Local Server > Ethernet properties > Internet Protocol Version 4 properties, I can assign the static IP. I used `192.168.122.0/24` network for this lab because it is the default from the NAT network, KVM's virtual router.
