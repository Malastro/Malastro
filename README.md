# Hola, soy Guillermo Cuevas 👋

Especializándome en **Ingeniería de Identidades (IAM)**, arquitecturas de directorio híbridas y seguridad del plano de control de identidad. Enfocado en el ciclo de vida de usuarios (JML), modelos de acceso de mínimo privilegio (Zero Trust / RBAC) y gobernanza en ecosistemas Microsoft (Active Directory & Entra ID).

---

### 🛡️ Gestión de identidades y accesos (IAM) | Mirador de Montepinar SL

Repositorio de laboratorios y proyectos prácticos de **Identity & Access Management (IAM)**, centrados en la gestión de identidades, la seguridad híbrida y el control de accesos mediante Active Directory y Microsoft Entra ID.

Todos los proyectos forman parte de un mismo caso de estudio: **Mirador de Montepinar SL**, una empresa donde las juntas de propietarios son un caos, las cuotas no siempre se pagan y la confianza brilla por su ausencia. El escenario perfecto para poner a prueba la seguridad de las identidades.

En Montepinar, cada vecino tiene sus propios problemas. En el entorno corporativo, esos problemas se traducen en retos de IAM:

- **Antonio Recio, mayorista no limpia pescado — El presidente que no se fía ni de su sombra.** Quiere saber quién entra, a qué accede y por qué. Su obsesión por controlar hasta el último movimiento sirve como escenario para trabajar la autenticación multifactor (MFA), las políticas de Acceso Condicional y la supervisión de los accesos. Aquí nadie entra por ser amigo del presidente.

- **Enrique Pastor, Concejal de Juventud y Tiempo Libre — El concejal de las normas y los procedimientos.** Entre sus discursos, sus cargos y sus intentos de poner orden, siempre hay una norma que aprobar. Su papel encaja con la gobernanza de identidades, la gestión de altas, cambios y bajas (JML), las revisiones de permisos y la trazabilidad de las operaciones. Porque hasta para cambiar de despacho hace falta el procedimiento adecuado.

- **Amador Rivas — El eslabón más imprevisible.** Si hay una contraseña fácil de adivinar o alguien dispuesto a pinchar en un enlace sospechoso, Amador podría ser el candidato perfecto. Su personaje permite explorar los riesgos de las credenciales débiles, la ingeniería social, el phishing y la importancia de proteger las cuentas con MFA. La contraseña `merengue123` no debería sobrevivir ni a la primera junta.

- **Maxi, alias «Mente Fría» — El rey de las soluciones improvisadas.** Si el camino oficial se complica, siempre puede aparecer una solución paralela montada desde el Max & Henry. Es el escenario ideal para hablar de *Shadow IT*: aplicaciones, servicios y accesos que escapan al control de la organización. Que algo funcione no significa que esté autorizado.

- **Coque — El conserje que necesita las llaves, pero no todas las llaves maestras.** Su trabajo exige acceso a determinadas tareas y recursos, no las llaves de todo el edificio. Representa el principio de mínimo privilegio, la separación de funciones y la necesidad de mantener cuentas de emergencia (*Break-Glass*) para situaciones excepcionales. Hasta Coque necesita límites, aunque tenga acceso al cuarto de contadores.

- **Izaskun y Mari Tere — Las que siempre encuentran la forma de enterarse de todo.** Entre cotilleos, visitas inesperadas y puertas que se quedan abiertas, representan los riesgos de las sesiones desatendidas, los accesos excesivos y las oportunidades de acceso no autorizado. En IAM, una puerta abierta no siempre es una puerta física.

- **Goya y Vicente — El salón, la tele y las sesiones que nunca se cierran.** Si el equipo se queda encendido mientras la vida sigue en el sofá, toca preguntarse cuánto tiempo debe mantenerse una sesión y cuándo conviene volver a verificar la identidad. Un escenario para estudiar los controles de sesión, la inactividad y las revisiones periódicas de acceso.

- **El moroso del 2.º C, Germán Palomares — El vecino al que nadie consigue localizar.** Las cuotas siguen sin aparecer y nadie sabe muy bien dónde está. En el entorno de seguridad, su ausencia recuerda que no siempre podemos confiar en el perímetro ni dar por hecho que todas las identidades están a salvo. El enfoque *Assume Breach* invita a prepararse para posibles compromisos, detectar comportamientos sospechosos y limitar el impacto de un acceso indebido.

## 🔧 Del caos vecinal al laboratorio técnico

Cada proyecto utiliza este universo ficticio para explorar problemas reales de identidad y acceso, documentando las configuraciones realizadas, las pruebas y las posibles mejoras.

El objetivo es construir un portfolio práctico de IAM que combine automatización, control de acceso, seguridad de identidades y documentación técnica. Porque en Mirador de Montepinar puede que nadie se fíe de nadie, pero al menos podemos comprobar quién tiene permiso para entrar.

| **Proyecto** | **Alcance técnico y casos de uso** | **Tecnologías y conceptos** | **Estado** |
|---|---|---|---|
| [**01 · Arquitectura de identidad híbrida**](https://github.com/Malastro/Hybrid-identity-lab) | Integración de Active Directory Domain Services (AD DS) con Microsoft Entra ID mediante sincronización de identidades. Filtrado por unidades organizativas (OU), sincronización de hashes de contraseña y automatización del aprovisionamiento de usuarios. | Windows Server 2022, AD DS, Microsoft Entra ID, Entra Connect Sync, PowerShell, PHS | `Completado` |
| [**02 · MFA y Acceso Condicional en Microsoft Entra ID**](https://github.com/Malastro/Lab_02-Entra_MFA) | Configuración de una política de acceso condicional que exige MFA. Preparación de cuentas de emergencia (*Break-Glass*), evaluación con What If, pruebas en modo *Report-only* y activación de la política. | Microsoft Entra ID, Conditional Access, MFA, Break-Glass, What If | `Completado` |
| [**03 · Ciclo de vida JML**](https://github.com/Malastro/Lab_03-Lifecycle-JML) | Automatización de altas, cambios y bajas con PowerShell. | AD DS, Powershell, Entra Connect Sync, JML, RBAC | `Implementado` |
| [**04 · SSO y aprovisionamiento de aplicaciones empresariales**](https://github.com/Malastro/Lab_04-SSO-y-Aprovisionamiento-de-Aplicaciones)| Integración de una aplicación empresarial con Microsoft Entra ID. Configuración y validación del inicio de sesión único (SSO), análisis de los flujos de autenticación y exploración del aprovisionamiento y desaprovisionamiento de usuarios cuando la aplicación lo permita. | Microsoft Entra ID, Enterprise Applications, SAML 2.0, OpenID Connect (OIDC), SCIM, federación de identidades | `Planificado` |
| **05 · Access Review & Gobernanza de Identidad (IGA)** |  |  | Planificado |

**Objetivo profesional:** desarrollar experiencia práctica en IAM mediante laboratorios reproducibles, documentación técnica y validación de configuraciones de seguridad.

---

📫 **Contacto:** [LinkedIn](https://www.linkedin.com/in/guillermocuevasarroyo)
