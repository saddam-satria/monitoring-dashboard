<p style="text-align: center; padding: 20px 0px;">
<img src="https://upload.wikimedia.org/wikipedia/en/thumb/a/a1/Grafana_logo.svg/1200px-Grafana_logo.svg.png" width="120" />
</p>

# System Monitoring

<img src="image.JPG" />

## - How To Running (Linux)

```
git clone https://github.com/saddam-satria/monitoring-dashboard.git

chmod +x run.sh

bash run.sh or ./run.sh

```

## - How To Running (Windows)

```
git clone https://github.com/saddam-satria/monitoring-dashboard.git

docker-compose -f container.yaml up -d
```

## - Configure Prometheus

when you have to reconfig prometheus, you can change it in prometheus folder, the config file connects as docker volume

## - Running Port

> Grafana => 3000

> Prometheus => 9090

> Node Exporter => 9100

<br>

<h3> made with ❤️ by Saddam Satria </h3>
<div style="padding: 10px 0px"> 
    <a href="https://www.linkedin.com/in/saddam-satria-ardhi-837570170/"><img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" style="width:40px; height: 40px; object-fit: contain;margin-right:10px;"/></a>
    <a href="https://www.instagram.com/saddamsatria_12/"><img src="https://cdn-icons-png.flaticon.com/512/1384/1384063.png" style="width:40px; height: 40px; object-fit: contain;"/></a>
</div>
