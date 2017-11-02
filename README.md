# apim-config

Add following to /etc/hosts
```
127.0.0.1 mysql-rdbms
127.0.0.1 analytics.apim.com
127.0.0.1 publisher.apim.com                    
127.0.0.1 sandbox.gw.apim.com                    
127.0.0.1 prod.gw.apim.com                       
127.0.0.1 km.apim.com                            
127.0.0.1 tm.apim.com                           
```

###### Port offset
```
publisher.apim.com : 0
sandbox.gw.apim.com : 10
prod.gw.apim.com: 11
km.apim.com: 5
tm.apim.com: 7
```

Create databases as mentioned in the master-datasource.xml
