# bash-config
A set a configuration routines for the bash shell

## References
* http://askubuntu.com/questions/391082/how-to-see-time-stamps-in-bash-history

#### Add date-timestamps to history
```
history
echo 'export HISTTIMEFORMAT="%Y-%m-%d %T "' >> ~/.bash_profile
source ~/.bash_profile
history
```

