# Moodle Openshift Images 
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


# Features

- Non-root
- Openshift Ready
- Automatic initial database

### Environments


| Environment | Details |
| ------ | ------ |
| TIMEZONE | Set Timezone (America/Montevideo, America/El_salvador) |
| WAITFOR_HOST | set name host |
| WAITFOR_PORT | set port for WAITFOR_HOST |



### How use in Openshift

```console

oc process -f moodle-openshift-template.yaml \ 
-p PUBLIC_DOMAIN=moodle.local.com  | oc create -f -

```

License
----

Martin vilche
