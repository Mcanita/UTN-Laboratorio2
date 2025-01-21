# Chango++ - Sistema de Gestión en C++

Chango++ es un proyecto desarrollado en C++ para gestionar proveedores, productos, clientes, ventas y usuarios. El sistema está diseñado para funcionar sin una base de datos, utilizando archivos para almacenar la información. Incluye un menú interactivo para **administradores** y **empleados**, con permisos específicos según el rol.

## Características Principales

- **Sistema Multiusuario**:
  - Roles de **Administrador** y **Empleado**.
  - Acceso restringido basado en el rol.
  
- **Gestión Modular**:
  - Proveedores, productos, clientes, ventas y usuarios.
  - Reportes detallados y configuraciones ajustables.

- **Interfaz de Consola Avanzada**:
  - Menús dinámicos con animaciones (`rlutil`).
  - Experiencia de usuario simplificada.

- **Sin Dependencia de Base de Datos**:
  - Los datos se almacenan en archivos binarios.
  - Sistema confiable y fácil de mantener.

## Menús Principales

### Menú Principal
El menú principal está dividido en dos opciones según el rol:

- **Administrador**: Acceso completo a todas las funcionalidades.
- **Empleado**: Acceso limitado al registro de productos, clientes y ventas.

## Cómo Ejecutar el Proyecto
Requisitos Previos:
- Compilador compatible con C++.
- Biblioteca rlutil.h para las animaciones en consola.
- Sistema operativo Windows (por la dependencia con windows.h).

## Instrucciones ##

1. Clona este repositorio:
```bash
git clone https://github.com/Mcanita/UTN-Laboratorio2.git

2. Accede a la carpeta del repositorio:
cd UTN-Laboratorio2

3. Compila el proyecto con tu IDE o compilador preferido.

4. Ejecuta el programa.

## Estructura del Proyecto ##
El proyecto utiliza un enfoque modular, con clases específicas para cada entidad clave:

**Proveedor:** Gestión de proveedores.
**Producto:** Control del inventario.
**Cliente:** Registro y administración de clientes.
**Venta:** Registro de operaciones comerciales.
**Usuario:** Administración de accesos y permisos.
**Carrito:** Manejo de items en compras.
Cada clase tiene su equivalente en:

- Funciones: Métodos adicionales para la manipulación de datos.
- Archivo: Gestión de los datos almacenados en archivos binarios.

**Créditos**  
Este proyecto fue desarrollado en colaboración por:  

- [Mcanita](https://github.com/Mcanita)  
- [BasiliscX](https://github.com/BasiliscX)


