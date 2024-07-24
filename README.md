# Exercise 1: Basic Package Management
## Objective: Install and remove packages on remote hosts.

- Install git on remote hosts.
- Remove apache2 if it exists.

# Exercise 2: File and Directory Management
## Objective: Manage files and directories on remote hosts.

- Create a directory /opt/myapp on remote hosts.
- Copy a configuration file myapp.conf from your local machine to /etc/myapp/myapp.conf on the remote hosts.
- Ensure the directory /opt/myapp has the correct permissions and ownership.

# Exercise 3: Service Management
## Objective: Start, stop, and enable services on remote hosts.

- Install nginx and ensure it is running.
- Enable nginx to start on boot.
- Stop and disable ufw (firewall) service.

# Exercise 4: User and Group Management
## Objective: Manage users and groups on remote hosts.

- Create a user deploy with a specific home directory and shell.
- Create a group developers and add the deploy user to this group.
- Ensure the deploy user has a specific SSH key in their ~/.ssh/authorized_keys file.

# Exercise 5: Cron Jobs
## Objective: Manage cron jobs on remote hosts.

- Create a cron job that runs a script /usr/local/bin/backup.sh every day at midnight.
- Ensure the cron job is owned by the root user.Objective: Manage cron jobs on remote hosts.

