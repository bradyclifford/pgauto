# pgforge
Automate your Postgres Migration Script Lifecycle

There is a perscription that is prescribed in managing your Postgres instances, however, you may includ your own templeting.

Examples of some future commands:

# Commands
```
pgforge init
```
```
pgforge init-instance
```
```
pgforge script <DB Story Ticket #>
```
* Creates an empty DDL script
```
pgforge template <DB Story Ticket #> --name --list
```
* Creates a DDL script from a template
```
pgforge rebase
```
```
pgforge create-db
```
```
pgforge destroy-db --removeRoles
```
```
pgforge migrate-db
```
```
pgforge instance --create --destroy --reset --init
```
