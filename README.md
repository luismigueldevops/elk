# docker ELK -  ElasticSearch, Logstash, and Kibana

### Ambiente en produccion
ElasticSearch se encuentra con su base de datos en estado persistente para produccion, se utliza EFS en AWS
el disco es montado en todos los servidores del cluster y dentro del disco se dejara al proyecto, esto con el fin de que todos nodos puedan escribir en el disco de datos persistentes de ELK.

 

