# Practica Redes
En prime lugar, se hallarían las direcciones IP de las subredes de la RED 1, todas ellas están conectadas a switches. 
A continuación, creamos la RED 2 que se caracteriza por tener un servidor (DHCP), al igual que la RED 3 y RED 4. A diferencia de las demás, la RED 4 también consta de un punto de acceso para conectar de forma inalámbrica a los ordenadores.
Después,asignamos un router para cada red exceptuando la primera.
Cada router debe ser configurado para conectar todas las redes, unas a otras. Para empezar se debe conectar HWIC-4ESW y WIC-2T a cada router. Además de ello, también hay que tener en cuenta para la configuración de los routers las direcciones de FastEthernet, la de las entradas Seriales, la declaración de cada red que forma parte del router en RIP y asignar la version 2 en CLI. Todas ellas deben estar conectadas y bien configuradas para su buen funcionamiento, de lo contrario habrán errores.
Por último, hay que configurar un servidor (DNS) para las distintas webs. Para ello, es importante poner la dirección DNS a todos los dispositivos, redes.
