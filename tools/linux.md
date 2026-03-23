# Linux

## Local vs Remote Awareness

- Distinguish local vs cloud execution
- Adapt commands accordingly
- Understand compute, storage, networking

## System

```bash
# Info
uname -a         # Kernel info
df -h            # Disk usage
free -h          # Memory
top/htop         # Processes

# Services
systemctl status # Service status
journalctl       # Logs

# Packages
apt search       # Search packages
dpkg -l          # Installed packages
```

## Performance

```bash
# CPU
lscpu            # CPU info
mpstat           # CPU stats

# Memory
vmstat           # VM stats
pmap             # Process memory

# I/O
iostat           # I/O stats
iotop            # I/O by process

# Identify bottlenecks
perf             # Profiling
strace           # System calls
```

## Async & Parallelism

- Identify parallel workloads
- Use async patterns
- Optimize IO vs CPU tasks
- Background jobs with &

## Container

```bash
docker ps        # Running containers
docker logs      # Container logs
docker exec      # Execute in container
docker-compose   # Multi-container
```

## Observability

- Design logging systems
- Add monitoring + metrics
- Debug using logs

## Security

```bash
# Users
whoami           # Current user
sudo -l          # Sudo permissions

# Firewall
iptables -L      # Rules
ufw status       # UFW status
```
