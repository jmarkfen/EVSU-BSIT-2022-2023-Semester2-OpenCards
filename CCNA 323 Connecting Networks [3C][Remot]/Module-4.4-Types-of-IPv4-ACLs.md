<!-- Module 4: ACL Concepts -->

<!-- 4.4: Types of IPv4 ACLs -->

## These permit or deny packets based only on the source IPv4 address.

- Standard ACLs

## These permit or deny packets based on the source IPv4 address and destination IPv4 address, protocol type, source and destination TCP or UDP ports and more.

- Extended ACLs

## Write command for extended ACL 100 permits traffic originating from any host on the 192.168.10.0/24 network to any IPv4 network if the destination host port is 80 (HTTP).

- access-list 100 permit tcp 192.168.10.0 0.0.0.255 any eq www

## Range of standard ACLs

- 1 to 99, or 1300 to 1999 

## Range of extended ACLs

- 100 to 199, or 2000 to 2699

## is the recommended method to use when configuring ACLs

- Named ACLs

## command used to create a named ACL

- ip access-list [standard|extended] [name]

## Extended ACLs should be located ____

- as close as possible to the source of the traffic to be filtered

## Standard ACLs should be located ____

- as close to the destination as possible. 