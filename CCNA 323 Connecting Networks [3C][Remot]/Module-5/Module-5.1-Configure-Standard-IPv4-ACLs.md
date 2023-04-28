<!-- Module 5: ACLs for IPv4 Configuration -->

<!--  5.1: Configure Standard IPv4 ACLs -->

## To create a numbered standard ACL, use the following global configuration command:

- `Router(config)# access-list access-list-number {deny | permit | remark text} source [source-wildcard] [log]`

## To create a named standard ACL, use the following global configuration command:

- `Router(config)# ip access-list standard access-list-name`

## The following command can be used to bind a numbered or named standard IPv4 ACL to an interface:

- `Router(config-if) # ip access-group {access-list-number | access-list-name} {in | out}`

## To remove an ACL from an interface, first enter the ____ interface configuration command. However, the ACL will still be configured on the router. To remove the ACL from the router, use the ____ global configuration command.

- `no ip access-group`
- `no access-list`

## use the ____ command to verify if an interface has an ACL applied to it

- `show ip interface`