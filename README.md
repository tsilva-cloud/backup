# backup
Insights relacionados ao ZDL

###  Listando os privilegios de sistema   ( DBA_SYS_PRIVS) : 

```
DESC DBA_SYS_PRIVS

 SELECT  *
 FROM DBA_SYS_PRIVS;
```

**Exemplo com filtro de GRANTEE :** 

```
 SELECT  * 
   FROM DBA_SYS_PRIVS
     WHERE GRANTEE LIKE 'ALIN%' ;
```

![image](https://github.com/user-attachments/assets/3d34ff7d-7a74-4da4-b639-026bbd379ad7)
