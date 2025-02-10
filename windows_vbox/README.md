# Docker Container Ports

**Container Web Ports**   
Webdav: 6999: http://10.17.0.10:6999/webdav   
Ledger: 7001 http://10.17.0.10:7001   
Boranga: 7002 http://10.17.0.10:7002   
Wildlife Legacy: 7005 http://10.17.0.10:7005   
Wildlife Compliance: 7006 http://10.17.0.10:7006   
Disturbance: 7007 http://10.17.0.10:7007  
Leases Licensing: 7008 http://10.17.0.10:7008   
Park Passes: 7009 http://10.17.0.10:7009   
Parkstay V2: 7010 http://10.17.0.10:7010   
Encryption GW: 7011 http://10.17.0.10:7011   
Commercial Operator: 7012 http://10.17.0.10:7012  
Moorings: 7013 http://10.17.0.10:7013  
Geoserver: 7014 http://10.17.0.10:7014  
Mooring Licensing: 7015 http://10.17.0.10:7015  
API Gateway: 7016 http://10.17.0.10:7016   
API Gateway: 7016 http://10.17.0.10:7016    
SQS: 7017 http://10.17.0.10:7017    
GIS Kaartdijin Boodja: 7018 http://10.17.0.10:7018    
APP Monitor: 7019 http://10.17.0.10:7019    
SSS Django: 7020 http://10.17.0.10:7020    
PBSV2 : 7021 http://10.17.0.10:7021     
IDAIS : 7022 http://10.17.0.10:7022   
System Maintenance 3: 7023 http://10.17.0.10:7023       
Queue Manager : 7024 http://10.17.0.10:7024     
Fee Waiver : 7025 http://10.17.0.10:7025     
PBSV1 : 7025 http://10.17.0.10:7026     
Geoserver2: 7026 http://10.17.0.10:7026  
Geoserver1_2.25: 7027 http://10.17.0.10:7027   
BFRS : 7028 http://10.17.0.10:7028   
Thermal Imaging Processing: 7029 http://10.17.0.10:7029  
BFRS Dfes Wrapper: 7030 http://10.17.0.10:7030   
Spatial Layer Monitor: 7031 http://10.17.0.10:7031     
SSS Maps: 7032 http://10.17.0.10:7032         
Statdev: 7033 http://10.17.0.10:7033    

**Container Dev Ports**   
Postgres: 9011-9020 http://10.17.0.10:9011   
Ledger: 9021-9030 http://10.17.0.10:9021   
Boranga: 9000-9010 http://10.17.0.10:9001  
Wildlife Legacy: 9041-9050 http://10.17.0.10:9041  
Wildlife Compliance : 9051-9060 http://10.17.0.10:9051  
Disturbance: 9061-9070 http://10.17.0.10:9061  
Leases Licensing: 9071-9080 http://10.17.0.10:9071  
Park Passes: 9081-9090 http://10.17.0.10:9081  
Parkstay V2: 9091-9100 http://10.17.0.10:9091   
Encryption GW: 9101-9105 http://10.17.0.10:9101    
Commercial Operator: 9106-9110 http://10.17.0.10:9106   
Moorings: 9111-9115 http://10.17.0.10:9111   
Geoserver: 9116-9120 http://10.17.0.10:9116   
Mooring Licensing: 9121-9125 http://10.17.0.10:9121   
API Gateway: 9126-9130 http://10.17.0.10:9126    
SQS: 9131-9135 http://10.17.0.10:9131    
GIS Kaartdijin Boodja: 9136-9140 http://10.17.0.10:9136     
APP Monitor: 9141-9145 http://10.17.0.10:9141         
SSS Django: 9146-9150 http://10.17.0.10:9146    
PBSV2: 9151-9155 http://10.17.0.10:9151         
IDAIS: 9156-9160 http://10.17.0.10:9156    
System Maintenance 3: 9161-9165 http://10.17.0.10:9161            
Queue Manager: 9166-9170 http://10.17.0.10:9166        
Fee Waiver: 9171-9175 http://10.17.0.10:9171     
PBSv1: 9176-9180 http://10.17.0.10:9176     
Geoserver2: 9181-9185 http://10.17.0.10:9181    
Geoserver1_2.25: 9186-9190 http://10.17.0.10:9186   
BFRS: 9191-9195 http://10.17.0.10:9191  
Thermal Imaging Processing:  9196-9200 http://10.17.0.10:9196    
BFRS Dfes Wrapper: 9201-9205 http://10.17.0.10:9201   
Spatial Layer Monitor: 9206-9210 http://10.17.0.10:9206    
SSS Maps: 9211-9215 http://10.17.0.10:9211    
Statdev: 9216-9220 http://10.17.0.10:9216     

**Container SSH Ports**   
Postgres: 2223    
Ledger: 2224   
Boranga: 2222   
Wildlife Legacy: 2225  
Wildlife Complance: 2226    
Disturbance: 2227   
Leases Licensing: 2228   
Park Passes: 2229   
Parkstay V2: 2230   
Encryption GW: 2231   
Commercial Operator: 2232   
Moorings : 2233      
Geoserver : 2234  
Mooring Licensing: 2235   
API Gateway : 2236   
SQS : 2237   
GIS Kaartdijin Boodja:  2238     
APP Monitor : 2239    
SSS Django : 2240    
PBSV2 : 2241   
IDAIS : 2242     
System Maintenance 3 : 2243    
Queue Manager : 2243    
Fee Waiver : 2244   
PBSv1 : 2245   
Geoserver2: 2246    
Geoserver_1_2_25: 2247   
BFRS: 2248

# Installation Instructions
https://github.com/dbca-wa/docker-scripts-dev/tree/main/windows_vbox/installation

# Update .bashrc to allow scripts to be executed anywhere.  

Add the two export lines to the end of the .bashrc   
   
```
vi ~/.bashrc   
export PATH=~/docker-scripts-dev/windows_vbox:$PATH   
export PATH=~/docker-scripts-dev/tools:$PATH   
```
