# readme
![image](https://github.com/mikkype/readme/assets/132553322/12f07834-7da6-47c2-8203-092314ce90bb)

asi  
y asi tenermos  

ahora podemos segui  
hola salto de linea  

y continuamos  
vamos a ver  


# como descaragar

>version: '3'
>services:
  >mysql:
    image: mysql
    environment:
      MYSQL_ROOT_PASSWORD : ${DB_PASSWORD}
      MYSQL_USER : ${DB_USER}
      MYSQL_DATABASE : ${DB_DATABASE}
    volumes:
      - mysql_node:/var/lib/mysql
    ports:
      - ${DB_PORT_MYSQL}:3306
volumes:
  mysql_node:




