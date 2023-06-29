# Prometheus Server
Prometheus is installed on AWS

#### Use prometheus-key.pem to access to it.
Add keys to your local machine:
chmod 400 "/Users/uladzislaubaluk/Downloads/prometheus-key.pem"

#### prometheus server is installed on amazon ec2
Prometheus is available here : 
```
http://18.220.20.52:9090/graph
```
Path to installed prometheus: 
```
/home/ec2-user/prometheus
```
Path to service setup on AWS instance:
```
/etc/systemd/system/prometheus.service
```

### Start:
sudo systemctl start prometheus

### Stop:
sudo systemctl stop prometheus

### Restart:
sudo systemctl stop prometheus