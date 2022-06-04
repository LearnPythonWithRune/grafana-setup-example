# grafana-setup-example
Grafana example setup for demonstration purpose

For Windows Powershell, Linux, or Mac
```bash
docker run -d -p 3000:3000 -v ${PWD}/grafana-data:/var/lib/grafana grafana/grafana
```

For Windows command
```bash
docker run -d -p 3000:3000 -v %cd%/grafana-data:/var/lib/grafana grafana/grafana
```
