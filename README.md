## Sawi 

Sawi is a tool to deploy `Django` projects based on [sawi template](https://github.com/vicobits/sawi)

## Installation

`[sudo] pip install git+https://github.com/vicobits/sawi-cli.git`

## Usage

#### Clone Sawi Django template

`git clone https://github.com/vicobits/sawi.git`

#### Add environment variables

The project must have a folder called `.envs` for environment variables por development
and a file `.env` for production with virtualenv deployment mode.

#### Add config file

By defaul `sawi` uses `django.json`, It is a file  that contains configuration values, following the next example:

```
{
    "deployment": "virtualenv",
    "project": "sawi",
    "password": "CHANGE_THIS!!",
    "domain": "www.xiberty.com",
    "ipv4": "0.0.0.0",
    "db_engine": "postgres",
    "web_server": "nginx",
    "https": true,
    "superuser": "root",
    "sshkey": "/Users/root/.ssh/id_rsa.pub"
}
```

## TODO
Expected commands

  [] `sawi install drone`
  [] `sawi install sentry`
  [] `sawi install harbor`
  [] `sawi install sonar`
  [] `sawi install taiga`
  [] `sawi install metabase`


NTH
https://github.com/goharbor/harbor
https://redash.io/
https://www.metabase.com/
https://passbolt.com/
https://github.com/documize/community
https://min.io/download#/linux
https://github.com/thedevs-network/kutt
https://github.com/outline/outline.  DOCUMENTATION


## Extra Config
For proxy config options check [dockerflow-proxy](http://proxy.dockerflow.com)
For letsencrypt config options check [dockerflow-le](https://github.com/n1b0r/docker-flow-proxy-letsencrypt)

License
-------
This code is licensed under the `MIT License`_.

.. _`MIT License`: https://github.com/vicobits/suarm/blob/master/LICENSE