# ajomex: Carro omnidireccional de 4 ruedas

Este repositorio contiene el diseño mecánico y los archivos de manufactura para el chasis de un robot móvil (Omni-wheel Rover) inspirado en la morfología del **Ajolote de Montaña (*Ambystoma altamirani*)**.

Este proyecto documenta el proceso de diseño desde el concepto inicial en papel hasta el modelo 3D final  para cuando se mande a corte láser.

##  Evolución del Diseño
El diseño final es el resultado de un proceso de abstracción geométrica:
1.  **Concepto Original:** Inspirado en la silueta y la cresta dorsal del ajolote de montaña.
2.  **Abstracción 2D:** Descomposición de las formas orgánicas en figuras geométricas aptas para manufactura.
3.  **Modelo Final:** Chasis estructural de dos niveles conectado por columnas rígidas, optimizando el espacio para motores, baterías y controladores.

## Especificaciones Técnicas
* **Software de Modelado:** Blender 4.0.
* **Material:** MDF de 3mm (Grosor verificado de 0.3cm en modelo).
* **Estructura:** Doble placa (Base y Top) con soportes verticales.
* **Manufactura:** Preparado para corte láser mediante archivos vectoriales (DXF/SVG). (Aun no esta Configurado)
* **Precisión:** Escala real aplicada (1:1) para asegurar la compatibilidad con componentes electrónicos estándar.

##  Metodología y Atajos Clave (Blender)
Para la realización de este chasis se emplearon técnicas esenciales de modelado de precisión:
- `N`: Panel de propiedades para asegurar el grosor exacto de **3mm** en el eje Z.
- `Ctrl + A`: Aplicación de escala para garantizar medidas reales en la exportación.
- `Shift + A`: Creación de primitivas para orificios de tornillería y ranuras de ventilación.
- `G / S / R + Ejes (X, Y, Z)`: Manipulación precisa de los componentes en el espacio 3D.
- `Herramienta de Medir`: Verificación visual de distancias entre barrenos.

##  Estructura del Repositorio
* `/blender`: Archivo fuente `.blend` (omni_4.blend).
* `/manufactura`: Planos 2D exportados para corte láser.
* `/diseño`: Bocetos iniciales y capturas del avance del modelo.
