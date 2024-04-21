---
tags: on/dev sources/article
---
# Aprender AWS

He comenzado el tutorial de serverless:

1. Instalar serverless


```
npm install serverless -g
```


2. Añadir  credenciales de aws
	

```
serverless config credentials --provider aws --key 1234 --secret 5678
```


- Se recomienda crear usuarios iam para restringir los permisos, pero
- ¿Qué permisos hacen falta para ejecutar funciones lambda?
	
	Referencias:
	https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html

dayone://view?entryId=0E17D160BF904992830BF529A533786D

---
**Metadata**
- Creation Date: 2021-06-23 20:40:01+02:00 (Europe/Madrid)
