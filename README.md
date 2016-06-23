Monitoring experimental deployment.

Supported Distros: 
Server: Ubuntu 14.04 LTS
Agent: Ubuntu 14.04 LTS, Ubuntu 16.04 LTS, CentOS 7.1

- azuredeploy.json

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fkarataliu%2Fxipdns%2Fmaster%2Fazuredeploy.json)

Deployment parameters:

| Parameters            | Description                                       |
| -------------         | -------------                                     |
| domain                | The top level domain.                             |

| Output                | Description                                       |
| -------------         | -------------                                     |
| NS1                   | IP Address for primary dns server                 |
| NS2                   | IP Address for secondary dns server               |

