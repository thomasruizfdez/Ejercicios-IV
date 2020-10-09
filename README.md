# Ejercicios-IV
Ejercicios de la asignatura Infraestructura Virtual 2020-2021

## Ejercicios Tema Introducción   
### Ejercicio 1  
**Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años.**  
Si comprásemos [este servidor](https://www.pccomponentes.com/servidor-fujitsu-primergy-intel-xeon-e3-1225v6-8gb-2tb) que cuesta 666€, ya que el valor de amortización está regulado a un 25% anual.
En 4 años el coste de amortización sería 666€ y en 7 años 1165€.

### Ejercicio 2  
**Usando las tablas de precios de servicios de alojamiento en Internet “clásicos”, es decir, que ofrezcan Virtual Private Servers o servidores físicos, y de proveedores de servicios en la nube, comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa solo el 1% o el 10% del tiempo.**  
Viendo las páginas de Rackspace y Amazon EC2 por servicios similares, variando lo mínimo posible,
La oferta de Rackspace sería 0.032$/h y la de Amazon EC2 0.059$/h(Tiene 2 vCPU).  
Usando el 1% del tiempo (87 horas):  
Rackspace: 2.784$  
Amazon EC2: 5.133$  
Usando el 10% del tiempo (876 horas):  
Rackspace: 28.032$  
Amazon EC2: 51.684$  

### Ejercicio 3  
**En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?**  
*flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx rdtscp lm constant_tsc arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf pni pclmulqdq dtes64 monitor ds_cpl vmx*  
Entre ellos aparece el flag vmx.  

### Ejercicio 4  
**Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios. Usar siempre que sea posible un hipervisor que sea software libre.**
He instalado Oracle VM (software libre) usando los paquetes binarias de su [web](https://www.virtualbox.org/).  
