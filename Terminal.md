Para desplegar la aplicación Let’s Chat que vimos en el punto anterior, ejecutamos la siguiente instrucción en el directorio donde tengamos el fichero docker-compose.yml:

$ docker-compose up -d
Creating network "letschat_default" with the default driver
Creating mongo ... done
Creating letschat ... done

Podemos ver los contenedores que se están ejecutando:

$ docker-compose ps
  Name               Command             State               Ports             
-------------------------------------------------------------------------------
letschat   npm start                     Up      5222/tcp, 0.0.0.0:80->8080/tcp
mongo      docker-entrypoint.sh mongod   Up      27017/tcp      

Podemos acceder desde el navegador a la aplicación:

ip/login

Podemos destruir el escenario:

$ docker-compose down 
Stopping letschat ... done
Stopping mongo   ... done
Removing letschat ... done
Removing mongo   ... done
Removing network letschat_default
