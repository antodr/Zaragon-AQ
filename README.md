
```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class About:
    def __init__(self):
        self.name = "Zaragon"
        self.role = "IT visionary"
        self.knowledge_base = [
            "Azure",
            "Prometheus",
            "Grafana",
            "Zabbix",
            "ELK stack",
            "RabbitMQ",
            ".NET",
            "Powershell",
            "Azure DEVOPS"
        ]
    
    def say_hi(self):
        print("""
        Hi there, I'm {name} and I'm an {role}.
        
        I'm working every days with {knowledge_base}.

        """.format(
            name= self.name,
            role = self.role,
            knowledge_base=", ".join(self.knowledge_base[0:])
        ))

me = About()
me.say_hi()
___

<p align="left"> <a href="https://azure.microsoft.com/en-in/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cs/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://dotnet.microsoft.com/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://grafana.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" alt="grafana" width="40" height="40"/> </a> <a href="https://www.elastic.co/kibana" target="_blank"> <img src="https://www.vectorlogo.zone/logos/elasticco_kibana/elasticco_kibana-icon.svg" alt="kibana" width="40" height="40"/> </a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank"></a> <a href="https://www.python.org" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.rabbitmq.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/rabbitmq/rabbitmq-icon.svg" alt="rabbitMQ" width="40" height="40"/> </a> </p>
