# FactuNER

**FactuNER** es un proyecto de código abierto diseñado para la extracción de información de facturas en formato PDF utilizando Modelos de Reconocimiento de Entidades Nombradas (NER, por sus siglas en inglés). El proyecto está enfocado en el contexto de América Latina, donde la falta de datasets específicos y etiquetados de facturas dificulta el desarrollo de soluciones eficientes para este tipo de documentos.

## Objetivo

El objetivo de **FactuNER** es proporcionar una herramienta poderosa y flexible que permita extraer de manera automatizada y precisa los datos clave de cualquier factura, como:

- Nombre del emisor
- Nombre del receptor
- Fecha de emisión
- Monto total
- Detalles de los productos/servicios
- Número de factura
- Impuestos y descuentos
- Y más...

El proyecto está orientado a empresas, desarrolladores y equipos de datos que necesiten trabajar con facturas en PDF y desean integrar la extracción de datos estructurados dentro de sus flujos de trabajo o aplicaciones.

## Características

- **Reconocimiento de Entidades Nombradas (NER)**: Utiliza técnicas avanzadas de procesamiento de lenguaje natural (NLP) para identificar y extraer entidades relevantes de facturas.
- **Soporte para Facturas en Español**: Dado el contexto latinoamericano, el modelo está entrenado para reconocer texto en español, con especial atención a las variantes locales de las facturas.
- **Entrenamiento y Personalización**: El modelo es entrenable, lo que permite adaptarlo a diferentes formatos de factura y a nuevos tipos de datos con ejemplos adicionales.
- **Compatibilidad con PDF**: Capacidad para procesar archivos PDF de facturas, independientemente de su formato o complejidad.
- **Open Source**: Totalmente libre y accesible para la comunidad, permitiendo la personalización y expansión del proyecto.
- **Fácil de Integrar**: El modelo está diseñado para ser sencillo de integrar en sistemas existentes, como plataformas de contabilidad, CRM, o sistemas de gestión empresarial (ERP).

## ¿Por qué FactuNER?

En América Latina, no existe una gran cantidad de datasets etiquetados con facturas para entrenamiento de modelos de NER, lo que complica el desarrollo de soluciones automatizadas de reconocimiento de facturas. **FactuNER** aborda este vacío proporcionando un modelo entrenado para reconocer los elementos esenciales de las facturas latinas, y es fácilmente ampliable con nuevos ejemplos de facturas para mejorar su precisión.

## Instalación

Para instalar **FactuNER** en tu entorno local, sigue los siguientes pasos:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/FactuNER.git
2. Instala las dependencias necesarias:
      ```bash
   pip install -r requirements.txt
3. Modifica el dataset, asi como la tokenizacion para adaptarla a tu proyecto, a medida que crezca se ira actualizando, para reconocer mas modelos de facturas diferentes.

## Como Contribuir
Si deseas contribuir al proyecto, por favor sigue estos pasos:

   
   1. Haz un fork de este repositorio.
   2. Crea una nueva rama para tu funcionalidad o corrección.
   3. Realiza los cambios y realiza un commit.
   4. Abre un Pull Request para que revisemos tu contribución.
   5. Agradecemos cualquier aporte, ya sea en forma de mejoras al código, correcciones de errores, o ejemplos de facturas que puedan enriquecer el dataset.



## LICENCIA
Este proyecto está licenciado bajo la MIT License, por lo tanto sientete libre de utilizar su informacion.

