# zeppelin-playground

```
java -jar /Users/stefan/apps/ili2pg-4.9.1/ili2pg-4.9.1.jar --dbhost localhost --dbport 54322 --dbdatabase pub --dbusr ddluser --dbpwd ddluser --dbschema alw_fruchtfolgeflaechen_pub --strokeArcs --defaultSrsCode 2056 --createEnumTabs --createMetaInfo --nameByTopic --createGeomIdx --models SO_ALW_Fruchtfolgeflaechen_Publikation_20220110 --createBasketCol --createDatasetCol --schemaimport
```

```
java -jar /Users/stefan/apps/ili2pg-4.9.1/ili2pg-4.9.1.jar --dbhost localhost --dbport 54322 --dbdatabase pub --dbusr ddluser --dbpwd ddluser --dbschema alw_fruchtfolgeflaechen_pub --models SO_ALW_Fruchtfolgeflaechen_Publikation_20220110 --disableValidation --dataset 2022 --import ch.so.alw.fruchtfolgeflaechen_2022.xtf
```


```
docker run -p 8080:8080 --rm --name zeppelin apache/zeppelin:0.10.1
```

```
./bin/zeppelin-daemon.sh start
tail -f logs/zeppelin-stefan-Monterrico.local.log
./bin/zeppelin-daemon.sh stop
```