1. ¿Cómo se inicializa un repositorio local? ¿Qué comando se debe ejecutar?
Para inicializar un repositorio local en Git, debes ejecutar el siguiente comando dentro del directorio del proyecto:
bash
CopiarEditar
git init
Este comando crea un nuevo repositorio de Git en el directorio actual.
2. ¿Cómo hago para que un directorio deje de ser controlado por Git? ¿Qué comando se debe ejecutar?
Para dejar de controlar un directorio con Git, puedes eliminar la carpeta oculta .git que contiene toda la configuración del repositorio:
bash
CopiarEditar
rm -rf .git
3. Si agrego un archivo a un directorio que ya está siendo controlado por Git, ¿está siendo controlado por Git?
No inmediatamente.
Git no rastrea automáticamente archivos nuevos. Si agregas un archivo nuevo, debes agregarlo manualmente con git add para que comience a ser rastreado.
4. ¿Qué comando se utiliza para agregar un archivo al repositorio local?
Usa este comando para agregar un archivo (o varios) al área de preparación (staging area):
bash
CopiarEditar
git add nombre_del_archivo
O para agregar todos los cambios:
bash
CopiarEditar
git add .

5. ¿Cómo determino qué archivos fueron modificados? ¿Qué comando se debe ejecutar?
bash
CopiarEditar
git status
6. ¿Qué comando se utiliza para hacer un commit?
El comando es:
bash
CopiarEditar
git commit -m "Mensaje del commit"

7.¿qué es un commit?
Un commit es como una fotografía del estado actual del proyecto. Representa un punto en el historial donde se guardan los cambios hechos en los archivos. Cada commit tiene un mensaje que explica qué se modificó y permite llevar un control del desarrollo del proyecto a lo largo del tiempo.
