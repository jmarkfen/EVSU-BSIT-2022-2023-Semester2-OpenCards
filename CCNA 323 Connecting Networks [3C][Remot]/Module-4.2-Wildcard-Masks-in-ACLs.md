<!-- Module 4: ACL Concepts -->

<!-- 4.2: Wildcard Masks in ACLs -->

## An IPv4 ACE uses a ____-bit wildcard mask to determine which bits of the address to examine for a match

- 32

## Match the corresponding bit value in the address

- Wildcard mask bit 0

## Ignore the corresponding bit value in the address

- Wildcard mask bit 1

## Match all octets.

- 0.0.0.0

## Wildcard to Match a Host

- 0.0.0.0 (match the whole address)

## Wildcard Mask to Match an IPv4 Subnet

- 0.0.0.255 (matches first three octets)

## Wildcard Mask to Match an IPv4 Address Range

- 0.0.15.255 (matches first two octets)

## Create ACL on 10, permit 192.168.10.10 host

- access-list 10 permit 192.168.10.10  0.0.0.0
- access-list 10 permit host 192.168.10.10