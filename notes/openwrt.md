

# openwrt
https://forum.openwrt.org/t/openwrt-support-for-d-link-dir-1960/66990/4

opkg install curl

# openwrt: prometheus
https://grafana.com/blog/2021/02/09/how-i-monitor-my-openwrt-router-with-grafana-cloud-and-prometheus/

opkg install prometheus-node-exporter-lua \
prometheus-node-exporter-lua-nat_traffic \
prometheus-node-exporter-lua-netstat \
prometheus-node-exporter-lua-openwrt \
prometheus-node-exporter-lua-wifi \
prometheus-node-exporter-lua-wifi_stations



# prometheus
* https://prometheus.io/docs/prometheus/latest/installation/
podman run --name myprometheus -d -p 9090:9090 -v /var/local/prometheus-etc:/etc/prometheus -v /var/local/prometheus-data:/data/db:Z prometheus 

# sm3lly: grafana
https://grafana.com/docs/grafana/latest/setup-grafana/installation/docker/#ubuntu-image

podman history docker.io/grafana/grafana-oss

grafana/grafana-oss:<version>-ubuntu
podman pull docker.io/grafana/grafana-oss

docker run -d -p 3000:3000 --name grafana  -v grafana-storage:/var/lib/grafana grafana/grafana-oss




