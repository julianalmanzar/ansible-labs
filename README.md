Este repositorio contiene archivos para los labs de ansible basicos que he realizado
El comando utilizado para ejecutar los playbooks es:

ansible-playbook -i [ruta archivo hosts] [Ruta al playbook] -e@./[Ruta al Vault File]  --vault-password-file ~/[Ruta al archivo que tiene el password del vault]

