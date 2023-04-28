<!-- Module 5: ACLs for IPv4 Configuration -->

<!--  5.4: Configure Extended IPv4 ACLs -->

## To create a numbered extended ACL, use the following global configuration command:

- `Router(config)# access-list access-list-number {deny | permit | remark text} protocol source source-wildcard [operator {port}] destination destination-wildcard [operator {port}] [established] [log]`

## commands for verifying ACLs

- `show ip interface`
- `show access-lists`
- `show running-config`

## command used to verify the ACL on the interface and the direction in which it was applied

- `show ip interface`

## command used to confirm that the ACLs work as expected

- `show access-lists`

## command can be used to validate what was configured

- `show running-config`