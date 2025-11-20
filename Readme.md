# Generador de Personas

![Java](https://img.shields.io/badge/Java-17-blue?style=flat-square)
![Maven](https://img.shields.io/badge/Maven-Build-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-En%20Desarrollo-yellow?style=flat-square)

Generador de personas aleatorias escrito en **Java** utilizando **Maven**.  
Carga datos de nombres, apellidos y dominios de email desde archivos de texto y genera perfiles completos con:

- **Nombre y apellidos**
- **Género** (hombre, mujer, prefiero no decirlo)
- **Teléfono** con prefijo internacional (+34)
- **Email** generado dinámicamente con reglas de formateo

---

## Características
- Lectura de archivos de texto para personalizar la base de datos.
- Generación de hasta **100.000 perfiles aleatorios**.
- Emails formateados con reglas personalizadas.
- Código documentado con **Javadoc**.
- Preparado para integrarse en otros proyectos.

---

## Estructura del Proyecto
```text
    .
    ├── datos/
    │ ├── nombre_hombres.txt
    │ ├── nombre_mujeres.txt
    │ ├── apellidos.txt
    │ └── all_email.txt
    ├── src/
    │ ├── main/java/com/example
    │ │ ├── App.java
    │ │ ├── ListaPersonas.java
    │ │ ├── Persona.java
    │ │ └── Genero.java
    │ └── test/java/com/example
    │ └── AppTest.java
    ├── pom.xml
    └── README.md
```

---

## Instalación y Uso
```bash
    # Clonar repositorio
    git clone https://github.com/tuusuario/generador-nombres.git
    cd generador-nombres

    # Compilar
    mvn clean package

    # Ejecutar
    java -cp target/generador-nombres-1.0-SNAPSHOT.jar com.example.App
```

---

## Generación de Javadoc
```bash
    mvn javadoc:javadoc
```
La documentación se genera en target/site/apidocs.

---

## Tecnologías Utilizadas

- **Java 17**

- **Maven** para gestión de dependencias y build

---

## Próximos Pasos

- Añadir interfaz gráfica (Swing / JavaFX)

- Añadir exportación de datos a CSV o JSON

- Mejorar las pruebas unitarias

- Publicar como librería Maven para facilitar su integración en otros proyectos

- Generar documentación automática con GitHub Pages


---

# Autor

**Gonzalo Chica Godino**

- chicagodinogonzalo@gmail.com

- [Perfil de GitHub](https://github.com/gonzalocg123)

---

# Licencia

Este proyecto se distribuye bajo la licencia **MIT**.  
Eres libre de usarlo, modificarlo y compartirlo, siempre mencionando al autor original.
