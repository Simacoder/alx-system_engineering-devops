#  0x0A. Configuration management

## Background Context


- When I was working for SlideShare, I worked on an auto-remediation tool called Skynet that monitored, scaled and fixed Cloud infrastructure. I was using a parallel job-execution system called MCollective that allowed me to execute commands to one or multiple servers at the same time. I could apply an action to a selected set of servers by applying a filter such as the server’s hostname or any other metadata we had (server type, server environment…). At some point, a bug was present in my code that sent nil to the filter method.

# Resources
Read or watch:

- [Intro to Configuration Management](https://intranet.alxswe.com/rltoken/GL30hu-aRcKzPOvK8JO-Bg)
- [Puppet resource type: file](https://intranet.alxswe.com/rltoken/WON0M4DNRabf88KAG_pDUA) (check “Resource types” for all manifest types in the left menu)
- [Puppet’s Declarative Language: Modeling Instead of Scripting](https://intranet.alxswe.com/rltoken/0V2fBdafkfKPMxA1umea3Q)
- [Puppet lint](https://intranet.alxswe.com/rltoken/CRUMeEMdcX-UtbWsUM9xLQ)
- [Puppet emacs mode](https://intranet.alxswe.com/rltoken/MzHXCntAkPzOqMnI6_rpWQ)

# Tasks
# 0. Create a file
- Using Puppet, create a file in /tmp.

# 1. Install a package
- Using Puppet, install flask from pip3.

# 2. Execute a command
- Using Puppet, create a manifest that kills a process named killmenow.

# AUTHOR
- Simanga Mchunu
