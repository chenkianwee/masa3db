# Visualisation with Grafana
## Install Grafana

1. If you have not installed Docker. Install Docker {doc}`21docker`.
2. If you have not installed Masa3DB. Install Masa3DB {doc}`23setup`.
3. Run this command to install Grafana.
    ```
    $ sudo docker run -d --network masa3db -p 3000:3000 --name grafana grafana/grafana  
    ```
4. Go to the server where you have installed your Grafana. In my case, I have installed it at http://chaosbox.princeton.edu:3000 (will need to VPN into the local intranet). For the first time, login to Grafana with username:admin and password:admin. Once login change the password and username.
