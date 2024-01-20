# Build Oracle Database 11g Express Edition container image

```bash
git clone https://github.com/asapoka/Oracle11gBuildContainerImage.git && \
cd Oracle11gBuildContainerImage && \
bash setup.bash
```

## test run container

```
docker run --rm --name 11g -p 1521:1521 -p 5500:5500 --shm-size=1g -e ORACLE_PWD=pass oracle/database:11.2.0.2-xe
```

please wait ...

```
########################
DATABASE IS READY TO USE!
#########################
```
