# Tarefa 3

# DDL1 Proxectos de investigación

Antes de crear as táboas que forman a base de datos, temos que creala. Simplemente utilizamos os seguintes comandos:

```SQL
CREATE DATABASE proxectos_de_investigacion; 
USE proxectos_de_investigacion;
```

Agora pódese comezar a crear as táboas dentro da BD que acabamos de crear. 

A BD **proxectos_de_investigacion** ten **9 táboas: Sede, Departamento, Ubicacion, Grupo, Profesor, Programa, Proxecto, Participa e Financia**. Temos que usar o comando `CREATE TABLE` para cada táboa, sempre indicando o seu nome, os atributos que forman a táboa, o tipo de dato de ditos atributos, a clave primaria e as posibles claves foráneas. Nalgunha das táboas engadiremos as claves foráneas mediante `ALTER TABLE`.

*Táboa **Sede** e táboa **Departamento*** ![captura1](https://github.com/pmareque/entrega-tarefas/blob/master/img/ddl1_1.PNG)

*Táboa **Ubicacion** e táboa **Grupo*** ![captura2](https://github.com/pmareque/entrega-tarefas/blob/master/img/ddl1_2.PNG)

*Táboa **Profesor*** ![captura3](https://github.com/pmareque/entrega-tarefas/blob/master/img/ddl1_3.PNG)

*ALTER TABLE **Departamento**, ALTER TABLE **Grupo**, táboa **Programa*** ![captura4](https://github.com/pmareque/entrega-tarefas/blob/master/img/ddl1_4.PNG)

*2 ALTER TABLE **Profesor** , `describe`= mostra a estructura completa da táboa(neste caso a táboa Profesor).* ![captura5](https://github.com/pmareque/entrega-tarefas/blob/master/img/ddl1_5.PNG)

*Táboa **Proxecto**, 2 ALTER TABLE **Proxecto*** ![captura6](https://github.com/pmareque/entrega-tarefas/blob/master/img/ddl1_6.PNG)
 
*Táboa **Participa**, táboa **Financia**, 2 ALTER TABLE **Financia*** ![captura7](https://github.com/pmareque/entrega-tarefas/blob/master/img/ddl1_7.PNG)

# DDL2 Naves espaciais

Do mesmo xeito que na base de datos anterior, utilizamos os comandos `CREATE DATABASE nome-taboa` e `USE nome-taboa`:

```SQL
CREATE DATABASE naves_espaciais; 
USE naves_espaciais;
```
Agora pasamos a crear as táboas dentro da nova BD. 

A BD **naves_espaciais** ten **8 táboas: Servizo, Dependencia, Camara, Tripulacion, Planeta, Visita, Habita e Raza**. En canto ás claves foráneas, engadiremos algunhas nos `CREATE TABLE ` como en constraints de `ALTER TABLE`. 

*Táboa **Servizo**, táboa **Dependencia*** ![capt1](https://github.com/pmareque/entrega-tarefas/blob/master/img/ddl2_1.PNG)

*Táboa **Camara**, táboa **Tripulacion**, ALTER TABLE **Tripulacion*** ![capt2](https://github.com/pmareque/entrega-tarefas/blob/master/img/ddl2_2.PNG)

*Táboa **Planeta**, táboa **Visita*** ![capt3](https://github.com/pmareque/entrega-tarefas/blob/master/img/ddl2_3.PNG)

*Táboa **Habita**, táboa **Raza**, ALTER TABLE **Habita**, ALTER TABLE **Camara*** ![capt4](https://github.com/pmareque/entrega-tarefas/blob/master/img/ddl2_4.PNG)

