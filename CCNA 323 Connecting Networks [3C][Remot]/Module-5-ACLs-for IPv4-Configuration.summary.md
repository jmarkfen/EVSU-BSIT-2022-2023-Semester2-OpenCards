<!-- Module 5: ACLs for IPv4 Configuration -->

## to create a numbered standard ACL, use

- ip access-list standard *access-list-number*

## to remove a numbered standard ACL, use

- no access-list *access-list-number*

## to verify if an interface has an ACL applied to it, use

- show ip interface

## To create a named standard ACL, use

- ip access-list standard *access-list-name*

## to remove a named standard IPv4, use

- no ip access-list standard *access-list-name*

## To bind a numbered or named standard IPv4 ACL to an interface, use

- ip access-group *{access-list-number | access-list-name}* *{ in | out }*

## Sequence numbers are automatically assigned when an ACE is entered. These numbers are listed in

- show access-lists

## command to clear the ACL statistics

- clear access-list counters
