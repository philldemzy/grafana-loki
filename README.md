### GRAFANA
[Installation of grafana](https://grafana.com/grafana/download?edition=oss&pg=oss-graf&plcmt=hero-btn-1)

Sample dashboard can be located in the `\config\grafana`


### LOKI
[Installation and setup of loki](https://grafana.com/docs/loki/latest/setup/install/)


### ALLOY
[You can install alloy from the website](https://grafana.com/docs/alloy/latest/set-up/install/)

The Setup below is to have different alloy configs for fetching logs from different environments
1. Change the **CONFIG_FILE** value in the **alloy** file you can check for the location for the file in the **alloy.service** file with key **EnvironmentFile** if you installed it on a linux machine
2. In path configured as value for **CONFIG_FILE** you can clreate multiple .alloy files to fetch logs from different environments e.g *Docker, Kubernetes, local files, e.t.c*

Sample `.alloy` config files can be located in the `\config\alloy` directory
Restart the alloy service after making changes


#### LOGQL
link to logql tutorials https://sbcode.net/grafana/logql/
