<!-- Module 5: ACLs for IPv4 Configuration -->

<!--  5.3: Secure VTY Ports with a Standard IPv4 ACL -->

## Use the following command to apply an ACL to the vty lines:

- `R1(config-line)# access-class {access-list-number | access-list-name} { in | out } `

## Sample way of securing VTY ports

```
R1(config)# username ADMIN secret class
R1(config)# ip access-list standard ADMIN-HOST
R1(config-std-nacl)# remark This ACL secures incoming vty lines
R1(config-std-nacl)# permit 192.168.10.10
R1(config-std-nacl)# deny any
R1(config-std-nacl)# exit
R1(config)# line vty 0 4
R1(config-line)# login local
R1(config-line)# transport input telnet
R1(config-line)# access-class ADMIN-HOST in
R1(config-line)# end
R1#
```

## In a production environment, you would set the vty lines to only allow SSH, as shown in the example.

```
R1(config)# line vty 0 4
R1(config-line)# login local
R1(config-line)# transport input ssh
R1(config-line)# access-class ADMIN-HOST in
R1(config-line)# end
R1#
```

