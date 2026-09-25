# Lab 05 — Linux Services, Logs and System Monitoring

## Objective

Learn how to monitor Linux services, investigate logs, and check server health.

## Commands Practiced

```bash
systemctl status ssh
sudo systemctl restart ssh
sudo systemctl stop ssh
sudo systemctl start ssh

journalctl -u ssh
journalctl -u ssh -n 20
journalctl -u ssh -f

top
free -h
df -h
du -sh /home/femi/*
ps aux
ps aux | grep ssh
```

## Skills Learned

* Checking service status.
* Restarting services.
* Reading Linux logs.
* Monitoring CPU usage.
* Monitoring memory usage.
* Checking disk usage.
* Investigating running processes.

## Screenshots

* SSH service status.
* SSH logs.
* Top command.
* Disk usage.
* Memory usage.
