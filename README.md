# Build Oracle Database 11g Express Edition container image

```bash
git clone https://github.com/asapoka/Oracle11gBuildContainerImage.git && \
cd Oracle11gBuildContainerImage && \
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
https://qiita.com/moriwakiii/items/e885407dc1dc018d4950
https://qiita.com/ishibashi-futoshi/items/3379598d5aefbeed16ab
https://qiita.com/okumuradd/items/e2c19a7130d7ad854e20
https://forums.oracle.com/ords/apexds/post/where-can-i-get-oracle-xe-11-2-0-1-0-x86-64-rpm-to-download-9915
https://github.com/oracle/docker-images/tree/main/OracleDatabase/SingleInstance
https://ryoichi0102.hatenablog.com/entry/2017/12/14/183046
