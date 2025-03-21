**View execution logs**
```
grep CRON /var/log/syslog | tail -n 20
```

```
crontab -e
crontab -l
```

**Behaviors**
- **cron jobs will be skipped** if your laptop is off or asleep at the scheduled execution time. Cron itself **does not retry or reschedule missed tasks**.
- Alternatives:
	- **anacron** for Linux
	- **launchd** for MacOS