# 💳 Alky-Wallet | Billetera Digital

> **Proyecto académico:** Aplicación web interactiva de gestión de finanzas personales con autenticación y transacciones digitales.

---

## 📋 Descripción del Proyecto

**Alky-Wallet** es una billetera digital educativa desarrollada como parte de un curso de desarrollo web. La aplicación permite a los usuarios gestionar sus finanzas a través de una interfaz intuitiva con funcionalidades de autenticación, depósitos, transferencias y visualización de transacciones.

### Características Principales

- ✅ **Autenticación de usuarios** - Sistema de login con validación de credenciales
- ✅ **Depósitos** - Función para depositar dinero en la cuenta
- ✅ **Transferencias** - Enviar dinero a otros usuarios
- ✅ **Historial de transacciones** - Registro completo de movimientos
- ✅ **Interfaz responsiva** - Diseño adaptable a dispositivos móviles
- ✅ **Navegación intuitiva** - Barra de navegación clara y accesible

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Descripción |
|-----------|-----------|
| **HTML5** | Estructura semántica de la aplicación |
| **CSS3** | Estilos personalizados y maquetación |
| **Bootstrap 5** | Framework CSS para componentes responsivos |
| **JavaScript (Vanilla)** | Lógica interactiva del lado del cliente |

---

## 📁 Estructura del Proyecto

```
ABPM2/
├── index.html              # Página de inicio
├── login.html              # Página de autenticación
├── deposit.html            # Página para realizar depósitos
├── sendmoney.html          # Página para enviar dinero
├── transactions.html       # Página de historial de transacciones
├── assets/
│   ├── css/
│   │   └── style.css       # Estilos personalizados
│   ├── img/                # Recursos de imagen
│   └── js/
│       ├── login.js        # Lógica de autenticación
│       ├── deposit.js      # Lógica de depósitos
│       ├── sendmoney.js    # Lógica de transferencias
│       └── transactions.js # Lógica del historial
└── README.md               # Documentación del proyecto
```

---

## 🚀 Instalación y Uso

### Requisitos Previos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- No requiere instalación de dependencias externas

### Cómo Ejecutar

1. **Clonar o descargar el repositorio:**
   ```bash
   git clone https://github.com/Cuuuni/ABPM2.git
   cd ABPM2
   ```

2. **Abrir en el navegador:**
   - Opción 1: Hacer doble clic en `index.html`
   - Opción 2: Usar un servidor local (recomendado)
     ```bash
     # Con Python
     python -m http.server 8000
     
     # Con Node.js (si tienes http-server)
     http-server
     ```

3. **Acceder a la aplicación:**
   - Navegar a `http://localhost:8000` (si usas servidor local)
   - O abrirla directamente en el navegador

### Credenciales de Prueba

Para probar la aplicación, usa una de estas credenciales:

| Email | Contraseña |
|-------|-----------|
| `usuario@gmail.com` | `123456` |
| `holaprofe@gmail.com` | `dosgatos` |

---

## 💻 Funcionalidades

### 1. Login
- Validación de credenciales contra base de datos simulada
- Alerta de confirmación al iniciar sesión
- Redirección automática a página principal

### 2. Depósito
- Interfaz para ingresar monto a depositar
- Validación de entrada
- Almacenamiento en sesión

### 3. Enviar Dinero
- Selección de destinatario
- Ingreso de cantidad
- Confirmación de transferencia

### 4. Transacciones
- Visualización de historial completo
- Registro de todas las operaciones realizadas
- Detalles de cada transacción

---

## 📝 Notas Técnicas

- **Base de Datos:** Simulada en JavaScript (localStorage/sessionStorage)
- **Estado:** Las transacciones se almacenan en sesión del navegador
- **Validación:** Implementada en el lado del cliente
- **Responsividad:** Totalmente adaptable a dispositivos móviles

---

## 👨‍💻 Autor

**Nombre:** [Constanza Lamas]  
**Correo:** [constanza.lamasv@gmail.com]  
**GitHub:** [@[Cuuuni]](https://github.com/[Cuuuni])  
**Institución:** BootCamp [SENCE]  
**Fecha de Entrega:** Junio 2026

---

## 📚 Referencias Educativas

- [MDN Web Docs - JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [Bootstrap 5 Documentation](https://getbootstrap.com/docs/5.0/)
- [HTML5 - Mozilla Developer Network](https://developer.mozilla.org/es/docs/Web/HTML)

---

## 📄 Licencia

Este proyecto es de carácter educativo. Desarrollado como trabajo académico.

---

## 🤝 Soporte

Si tienes preguntas o sugerencias sobre el proyecto:
- Abre un [Issue](https://github.com/Cuuuni/ABPM2/issues) en GitHub
- Contacta al autor

---

**Última actualización:** Junio 2026
