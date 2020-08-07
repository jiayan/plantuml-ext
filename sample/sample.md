# sample

样例

```plantuml
@startuml
!include ../dist/c4-container.puml
!include ../dist/spirites/all.puml


ContainerMyDatabaseMysql(a1,"123","abc")

ContainerMyDatabaseRedis(a2,"123","abc")

ContainerMyDatabaseRabbitmq(r,"123","abc")

ContainerMyDatabasElasticSearch(e,"123","abc")

ContainerMyDatabasFile(f,"123","abc")

ContainerMyDatabasMongoDb(m,"123","abc")

ContainerMyDatabasPhp(p,"123","abc")

EntityWarehouse(w1,"ab","abc")

@enduml
```

