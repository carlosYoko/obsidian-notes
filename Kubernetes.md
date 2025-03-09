
- **Definiciones**
	* Clúster
			- Es un conjunto de máquinas de nodos que ejecutan aplicaciones en contenedores. Al ejecutar Kubernetes, se está ejecutando un clúster.
	* Nodo
			- Es una máquina de trabajo en Kubernetes, previamente conocida como minion . Un nodo puede ser una máquina virtual o física, dependiendo del tipo de clúster. Cada nodo está gestionado por el componente máster y contiene los servicios necesarios para ejecutar pods.

---

- **Comandos**
	- Listar espacios de nombres
			- $ kubectl get namespaces
	- Mostrar los pods en el espacio de nombre actual
			- $ kubectl get pods
	- Mostrar los pods en el espacio de nombre indicado
			- $ kubectl get pods -n <nombre-espacio>