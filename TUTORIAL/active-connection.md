# How To Check Active Connections in Windows

```
1. open cmd
2. type: netstat -a (shows all the currently active connections and the output display the protocol, source, and destination addresses along with the port numbers and the state of the connection)
3. type: netstat -b (shows the executable involved in creating each connection or listening port. Please note that we need extra privileges to execute this output. We might see the following error)
4. type: netstat -n (shows similar outputs with IP addresses rather than names of system or services)
5. type: netstat /? (shows all the options available with the command)
```
