<!-- Module 5: ACLs for IPv4 Configuration -->

<!--  5.2: Modify IPv4 ACLs -->

## two methods to use when modifying an ACL

- Text Editor
- Sequence Numbers

## Steps in modifying an ACL using a text editor

- Copy the ACL from the running configuration and paste it into the text editor.
- Make the necessary edits changes.
- Remove the previously configured ACL on the router otherwise, pasting the edited ACL commands will only append (i.e., add) to the existing ACL ACEs on the router.
- Copy and paste the edited ACL back to the router.


## Steps in modifying an ACL using sequence numbers

- use `show access-lists` command
- use `ip access-list standard|extended` command
- use `no [access-list-number]` to remove a numbered ACL first
- use `[access-list-number] [permit|deny|remark] ..` to change the ACEs of the access list number