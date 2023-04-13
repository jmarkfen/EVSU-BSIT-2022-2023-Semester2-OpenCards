<!-- Module 6: NAT for IPv4 -->

## provides the translation of private addresses to public addresses

- Network Address Translation (NAT)

## The address of the device which is being translated by NAT.

- Inside address

## The address of the destination device.

- Outside address

## is any address that appears on the inside portion of the network.

- Local address

## is any address that appears on the outside portion of the network.

- Global address

## Types of NAT

- Static NAT
- Dynamic NAT
- PAT

## uses a one-to-one mapping of local and global addresses. These mappings are configured by the network administrator and remain constant

- Static NAT

## uses a pool of public addresses and assigns them on a first-come, first-served basis

- Dynamic NAT

## also known as NAT overload, maps multiple private IPv4 addresses to a single public IPv4 address or a few addresses

- Port Address Translation (PAT)

## This is the most common form of NAT for both the home and the enterprise.

- Port Address Translation (PAT)

## to create a mapping between the inside local address and the inside global addresses, use

- `ip nat inside source static`

## To verify NAT operation use

- `show ip nat translations`

## to clear records of pat NAT translations, use

- `clear ip nat statistics`

## 