##  Arquitectura Docker 

Por ejemplo:

```bash
» docker-machine inspect default 
```


```json
{
    "ConfigVersion": 3,
    "Driver": {
        "IPAddress": "192.168.99.100",
        "MachineName": "default",
        "SSHUser": "docker",
        "SSHPort": 57894,
        "SSHKeyPath": "C:\\Users\\user\\.docker\\machine\\machines\\default\\id_rsa",
        "StorePath": "C:\\Users\\user\\.docker\\machine",
        "SwarmMaster": false,
        "SwarmHost": "tcp://0.0.0.0:3376",
        "SwarmDiscovery": "",
        "VBoxManager": {},
        "CPU": 1,
        "Memory": 1024,
        "DiskSize": 20000,
        "Boot2DockerURL": "",
        "Boot2DockerImportVM": "",
        "HostDNSResolver": false,
        "HostOnlyCIDR": "192.168.99.1/24",
        "HostOnlyNicType": "82540EM",
        "HostOnlyPromiscMode": "deny",
        "NoShare": false,
        "DNSProxy": false,
        "NoVTXCheck": false
    },
    "DriverName": "virtualbox",
    "HostOptions": {
        "Driver": "",
        "Memory": 0,
        "Disk": 0,
        "EngineOptions": {
            "ArbitraryFlags": [],
            "Dns": null,
            "GraphDir": "",
            "Env": [],
            "Ipv6": false,
            "InsecureRegistry": [],
            "Labels": [],
            "LogLevel": "",
            "StorageDriver": "",
            "SelinuxEnabled": false,
            "TlsVerify": true,
            "RegistryMirror": [],
            "InstallURL": "https://get.docker.com"
        },
        "SwarmOptions": {
            "IsSwarm": false,
            "Address": "",
            "Discovery": "",
            "Master": false,
            "Host": "tcp://0.0.0.0:3376",
            "Image": "swarm:latest",
            "Strategy": "spread",
            "Heartbeat": 0,
            "Overcommit": 0,
            "ArbitraryFlags": [],
            "Env": null
        },
        "AuthOptions": {
            "CertDir": "C:\\Users\\user\\.docker\\machine\\certs",
            "CaCertPath": "C:\\Users\\user\\.docker\\machine\\certs\\ca.pem",
            "CaPrivateKeyPath": "C:\\Users\\user\\.docker\\machine\\certs\\ca-key.pem",
            "CaCertRemotePath": "",
            "ServerCertPath": "C:\\Users\\user\\.docker\\machine\\machines\\default\\server.pem",
            "ServerKeyPath": "C:\\Users\\user\\.docker\\machine\\machines\\default\\server-key.pem",
            "ClientKeyPath": "C:\\Users\\user\\.docker\\machine\\certs\\key.pem",
            "ServerCertRemotePath": "",
            "ServerKeyRemotePath": "",
            "ClientCertPath": "C:\\Users\\user\\.docker\\machine\\certs\\cert.pem",
            "ServerCertSANs": [],
            "StorePath": "C:\\Users\\user\\.docker\\machine\\machines\\default"
        }
    },
    "Name": "default"
}

```
<!-- .element: class="fragment"  -->