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

## To configure dynamic NAT, first define the pool of addresses that will be used for translation using

- `ip nat pool`

## to control which addresses will only be translated, bind an ACL to the NAT pool using

- `nat inside source list *{access-list-number | access-list-name}* pool *pool-name*`

## this command displays all static translations that have been configured and any dynamic translations that have been created by traffic

- show ip nat translations

## by default, translation entries time out after ____ hours

- 24

## to configure the amount of time before NAT translations are cleared, use

- `ip nat translation timeout *timeout-seconds*`

## To configure PAT to use a single IPv4 address, simply add the keyword ____ to the `ip nat inside source` command

- `overload`

## To configure PAT for a dynamic NAT address pool, simply add the keyword ____ to the `ip nat inside source` command

- `overload`

## IPv6 private address space is called

- unique local addresses (ULAs)

<!-- extra -->

## Advantages of NAT

- conserves legally registered addresses by allowing the privatization of intranets
- increases the flexibility of connections to the public network
- provides consistency for internal network addressing schemes
- hides the IPv4 addresses of users and other devices

## Disadvantages of NAT

- network performance, especially for real time protocols such as VoIP
- forwarding delays caused by the NAT process becomes more of an issue as the pools of public IPv4 addresses for ISPs become depleted
- end-to-end addressing is lost
- End-to-end IPv4 traceability is lost
- complicates the use of tunneling protocols, such as IPsec
- Services that require the initiation of TCP connections from the outside network, or stateless protocols can be disrupted

## process of two layers of NAT translations
- Carrier Grade NAT (CGN)