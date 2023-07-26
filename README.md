# DDEV Issue 5196

This repository is a trivial example for [this github issue](https://github.com/ddev/ddev/issues/5196) 
and this [discord conversation](https://discord.com/channels/664580571770388500/1133658524967260252/1133658524967260252).

Just start this project with `ddev start` and you should get this error:

```shell
Failed to start ddevIssueDemo: ComposeCmd failed to run 'COMPOSE_PROJECT_NAME=ddev-ddevissuedemo docker-compose -f /home/user/.ddev/.router-compose.yaml config', action='[config]', err='exit status 15', stdout='', stderr='validating /home/user/.ddev/.router-compose.yaml: services.ddev-router.ports array items[7,8] must be unique'
```