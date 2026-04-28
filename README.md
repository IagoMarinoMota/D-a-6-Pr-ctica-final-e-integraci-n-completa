# Uso del chart
Para poder usar este umbrella chart, tenemos que usar como principal el chart de `mi-stack`.
Despues de esto usaremos el comando `helm dependency update` por si las dependencias no se actualizaron al descargar los charts.
Al actualizar las dependecias, podemos hacer un `helm template` y un `helm lint`.

Los resultados de estos comandos son los siguientes:

`helm lint`: <img width="2880" height="1752" alt="Captura de pantalla de 2026-04-28 09-09-38" src="https://github.com/user-attachments/assets/cbd79b19-276d-44b6-a98b-dbc9016c98bf" />

`helm template`: 
<img width="2880" height="1752" alt="Captura de pantalla de 2026-04-28 09-08-47" src="https://github.com/user-attachments/assets/c22cce22-e3a1-49c5-86ac-a6ddd5d4e6d0" />
<img width="2880" height="1752" alt="Captura de pantalla de 2026-04-28 09-08-59" src="https://github.com/user-attachments/assets/d6007a74-6ed6-4ebe-b83d-f736f0ec602e" />
<img width="2880" height="1752" alt="Captura de pantalla de 2026-04-28 09-09-05" src="https://github.com/user-attachments/assets/3c704985-9aec-4b1c-94e3-c87627d64b7f" />

Ahora que tenemos esto comprobado, tenemos que instalar el chart. Para instalarlo usamos el comando `helm install`:
<img width="2880" height="1752" alt="Captura de pantalla de 2026-04-28 10-18-20" src="https://github.com/user-attachments/assets/39aed4fb-52ef-44d0-84bf-1910fe9d4830" />
