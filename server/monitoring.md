# Monitoring

**1. Name tools for monitoring services.**
- Nagios
- New relic
- Prometheus
**2. How to know which ports are open ?**
On a Linux system :
`netstat`
**3. How to monitoring network trafic ?**
On Linux :
`vnstat`
**4. How to test rest calls ?**
There's browser extensions that allows to test a rest call.
There's also tools such as `Postman` that allows to monitor specific URL.
It is also advisable to add tests for defined APIs which will be executed in the continuous integration pipeline.
**5. How to check dns resolution?**
`nslookup [name]`
**6. How to check if an ip is responding ?**
`ping [ip]`
**7. Where are the logs on linux ?**
`/var/log/`
**8. How to start, stop and check the status of a service on Linux ?**
It depends of the distro.
Most of them use systemctl :
- `systemctl start [service]`
- `systemctl stop [service]`
- `systemctl status [service]`
**9. How to monitor deployment ?**
Many cloud providers offer a tool to monitor deployment.
Otherwise, a tool like `New Relic` allows to monitor deployment.
**10. How to ensure a server or a container is responding ?**
Use a tool such as Prometheus or DynaTrace.