
- **Definiciones**
	* Clúster
			- Es un conjunto de máquinas de nodos que ejecutan aplicaciones en contenedores. Al ejecutar Kubernetes, se está ejecutando un clúster.
	* Nodo
			- Es una máquina de trabajo en Kubernetes, previamente conocida como minion . Un nodo puede ser una máquina virtual o física, dependiendo del tipo de clúster. Cada nodo está gestionado por el componente máster y contiene los servicios necesarios para ejecutar pods.
	* Rolling Updates
			- Se basa en utilizar la estrategia de tipo “RollingUpdate” de un deployment de Kubernetes, donde se genera un replicaset paralelo con nuevos pods de la nueva versión del software. Estos pods no reciben tráfico hasta que la nueva versión está desplegada.
	* Kubelet
			- Es el “agente Kubernetes ”, un servicio que se ejecuta en cada nodo Kubernetes y es responsable de crear el contenedor según las instrucciones del plano de control.
	* etcd
			- Es un **almacén de valores clave distribuido de código abierto** que se utiliza para almacenar y administrar la información crítica que los sistemas distribuidos necesitan para seguir funcionando.

---

- **Comandos**
	- Listar espacios de nombres
			- $ kubectl get namespaces
	- Mostrar los pods en el espacio de nombre actual
			- $ kubectl get pods
	- Mostrar los pods en el espacio de nombre indicado
			- $ kubectl get pods -n <nombre-espacio>