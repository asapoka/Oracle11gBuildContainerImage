# Build Oracle11 container image

```bash
git clone
cd Oracle11gBuildContainerImage
. setup.bash
```

## run container

```
docker run -d --name 11g -p 1521:1521 -p 5500:5500 --shm-size=1g -e ORACLE_PWD=pass oracle/database:11.2.0.2-xe
```
