
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

```