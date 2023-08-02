# Dashboards de Grafana

Este repositorio contiene Dashboards de Grafana mantenidos por los expertos de Conectate.  
Existen dashboards diseñados a medida en la página de Grafana, los cuáles utilizamos cómo base y adaptamos a necesidades especificas y vamos manteniendo actualizados en función a mejoras que permitan una mejor visualización y/o customización a distintos casos de uso.

> De igual manera lo invitamos a visitar el repositorio oficial de dashboards de Grafana en el siguiente botón
[Dashboards de Grafana](https://grafana.com/grafana/dashboards/)

## Cómo utilizar los dashboards de este repositorio

Los dashboards está separados por categorías, las cuáles iremos actualizando a medida que se vayan modificando/creando nuevos dashboards.

| Categoría | Description |
| ----------- | ----------- |
| Networking | Dispositivos de red cómo Routers, Switches, APs, Firewalls, etc. |
| Servidores | Servidores con Sistema Operativo Linux o Windows  |
| Base de datos | Motores de base de datos  |

En función a lo expuesto, los pasos a seguir para utilizar un dashboard son:

1. Identificar el tipo de Dashboard que estamos necesitando, por ejemplo para un dispositivo Fortinet:  
    - Seleccionamos la categoría adecuada, en este caso **Networking**  
    - Seleccionamos y descargamos el dashboard correcto, en este caso:     **Fortigate Prometheus Exporter Conectate.json**  
    - Una vez descargado el dashboard, debemos acceder a la siguiente URL:  
    https://customer.conectate.io/dashboard/import  dónde el valor **customer** debe coincidir con el ID de su cuenta en el servicio ofrecido por Conectate  
        > **Estos tableros también pueden ser utilizados en instancias de Grafana distintas a las mantenidas por Conectate, en este caso la URL debería coincidir con la URL de acceso utilizada por su instancia de Grafana**

