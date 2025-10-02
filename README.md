Netdata-Monitoring
 Monitor System Resources Using Netdata
 Objective: Install Netdata and visualize system and app performance metrics.
 Tools: Netdata (free, open-source monitoring tool), Docker
 Deliverables: Screenshot of the dashboard and running metrics
 Mini-Guide (Hints):
 Run via Docker: docker run -d --name=netdata -p 19999:19999 netdata/netdata
 Access at http://localhost:19999
 Monitor CPU, memory, disk, Docker containers
 Explore alerts and chart panels
 Explore logs in /var/log/netdata
 Outcome: Understand lightweight monitoring for servers or app
