Estos dos scripts nos ayudan en ataques shellshock, el primero nos establece una revershe shell, para ello cambiar la configuración y poner vuestra IP y establecer un puerto de escucha con netcat.

En cuanto al segundo script, os permite ejecutar comandos en la URL vulnerable a este tipo de ataque. 

Recomendado poner el comando entre dobles comillas ""

# USO shellshock

----
```
python3 shellshock.py <url_vulnerable>

```
----

# USO shellshock2.py

----
```
python3 shellshock.py <URL> <comando>

```
----

![image](https://github.com/user-attachments/assets/101da165-a27b-4f6e-a674-8ad5c6802522)

