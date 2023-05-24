# Practica con cheekmonkey

Edmundo Gomez Alvarez 

### Introduccion

Es una herramienta que se utiliza para realizar pruebas de estrés y carga en aplicaciones y servicios desplegados en entornos de Kubernetes. Fue desarrollada con el objetivo de facilitar la validación de la escalabilidad y el rendimiento de las aplicaciones en clústeres de Kubernetes.

En un entorno de Kubernetes, donde las aplicaciones se despliegan en contenedores y se escalan automáticamente según la demanda, es crucial asegurarse de que el sistema pueda manejar eficientemente cargas altas y picos de tráfico sin experimentar degradación del rendimiento o interrupciones del servicio.

Cheekymonkey proporciona una manera sencilla de simular una alta carga de usuarios o tráfico en una aplicación desplegada en Kubernetes. Permite definir perfiles de carga personalizados, configurar escenarios de prueba y realizar pruebas de estrés para evaluar cómo se comporta la aplicación en condiciones de alta demanda.

Al utilizar Cheekymonkey, puedes generar tráfico sintético en tu aplicación, simular diferentes patrones de uso y evaluar la capacidad de respuesta de tu infraestructura. Esto te ayuda a identificar cuellos de botella, ajustar la configuración de escalado automático de Kubernetes y optimizar la arquitectura de tu aplicación para obtener un rendimiento óptimo.

### Desarrollo

En esta práctica, además de utilizar Cheekymonkey para realizar pruebas de estrés en entornos de Kubernetes, también se utilizará Locust para verificar si la página objetivo se ha caído o sigue en funcionamiento. Locust es una herramienta ideal para este propósito, ya que permite simular el comportamiento de usuarios reales y monitorear continuamente el estado de la página durante las pruebas de carga.

Se utilizará en una página web alojada en Azure.

![install](https://github.com/edez5558/practice-cheekmonkey/assets/122659695/5abdd8d9-e5c4-4503-a471-cae00db31bdc)


![start](https://github.com/edez5558/practice-cheekmonkey/assets/122659695/71f97ab1-56ea-479f-b325-1785266fd747)

![game_1](https://github.com/edez5558/practice-cheekmonkey/assets/122659695/b1bdf52a-3c68-42c4-8b97-fe66e69e746b)

Los pods que se encuentran en los kubernetes son los siguientes:

![pods](https://github.com/edez5558/practice-cheekmonkey/assets/122659695/915087cf-29d5-4975-aa73-4cb38d2c821c)

![locust_2](https://github.com/edez5558/practice-cheekmonkey/assets/122659695/48041e33-7d81-4629-a975-f3b2ef2c1714)

Aqui juntamos tres cajitas para destruirlas juntas y ver si se cae

![game_3box](https://github.com/edez5558/practice-cheekmonkey/assets/122659695/f0ffe577-f353-4771-acfb-4b309cbdbb4e)

Parece que el servicio aun no se cae

![nofall](https://github.com/edez5558/practice-cheekmonkey/assets/122659695/95dbc36f-fac5-4eba-9300-30c2a8d09624)

Aquí se muestra la gráfica final que nos proporciona Locust. Durante las pruebas de carga


![info](https://github.com/edez5558/practice-cheekmonkey/assets/122659695/a954d791-15bf-4bcc-abff-e84de24a09b4)

![chart](https://github.com/edez5558/practice-cheekmonkey/assets/122659695/be26a7bd-5ac8-41f8-938e-235a9daf4cc1)

