# Fail2ban filters to protect NginX

Each filter has 2 parts:

- a configuration part that is in /etc/fail2ban/jail.local
- a definition part that is in a file in /etc/fail2ban/filter.d/<filter>.conf

To add a filter add it's definition to jail.local and copy the definition file