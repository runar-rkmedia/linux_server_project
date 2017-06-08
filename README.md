# linux_server_project
Udacity assignment.

The goal of this assignment is to configure a linux-server to be secure, while serving a web-application which has a database in PostGreSQL.

The web-application served here is from an earlier assignment.



## Accessing the server

You will need a key to access. If you are a reviewer, go ahead and connect.

```
ip: 52.214.216.190
ssh-port: 2200
url: http://52.214.216.190/
```

## Software installed

- git
- python3 (with dev)
- PostGreSQL
- All software updated and upgraded

## Configuration-changes

### Ports

Port was changed from 22 to 2200, with both Lightsail- and UFW-firewalls changes to allow only SSH, HTTP and NTP as per instructions.

### Authorization

New user with account-name called *grader*, with *sudo*-access, only allowed to connect over SSH.

### PostGreSQL

Only allowing local connections. New user called *catalog* which only has limited access to the database *catalog*.

### Third Party Resources used

- [PostGreSQL-documentions](https://www.postgresql.org/docs/)
- [Lightsail-documentation](https://lightsail.aws.amazon.com/ls/docs/all)
- StackOverflow
- Google
- Udacity-community
