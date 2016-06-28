Shared Hosting Foo
===================

Toolset for managing team machines, where you allow users to access machine and configure/reserve
some shared resources.

Resources to be shared:
- shared web server: 
    - user can create/remove sites (static, php, node)
    - user can start/restart/stop its apps
    - user can see logs of his site
- (f) shared PostgreSQL instance with many databases per user
- (f) redis instances on demand
- managed backup with history (rdiff-backup for now)

Permisions must be based on UNIX user/group model.

Future extra features:
- distrubuted resource alloc comission site on A (part of cluster C) and it runs on random device
- distrubuted storage (GluusterFS across cluster ?)

Terms & definitions:
- each service has unique NAME
- 

