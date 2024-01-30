# Build Oracle Database 11g Express Edition container image

```bash
git clone https://github.com/asapoka/Oracle11gImage.git && \
cd Oracle11gImage && \
bash setup.bash
```

## test run container

```
docker compose up
```

please wait ...

```
########################
DATABASE IS READY TO USE!
#########################
```

test sqlplus

```
docker exec -it 11g sqlplus sys/pass@XE as sysdba
```

thanks!
https://github.com/oracle/docker-images/tree/main/OracleDatabase/SingleInstance
