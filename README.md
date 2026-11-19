# Práctica RA5 - Lucas Aldave

---

## A5.1 - Filtres al Gmail

### 1. Llistat de sis eines de Google (eina, propòsit, target)

| Eina | Propòsit | Target (Públic objectiu) |
| :--- | :--- | :--- |
| **Gmail** | Servei de correu electrònic per enviar, rebre i organitzar missatges. | Usuaris particulars, estudiants i empreses. |
| **Google Drive** | Emmagatzematge al núvol per desar, compartir i sincronitzar arxius. | Estudiants, professionals i equips de treball. |
| **Google Calendar** | Agenda i calendari digital per planificar esdeveniments, reunions i recordatoris. | Usuaris particulars, docents i professionals. |
| **Google Docs** | Processador de textos en línia que permet l'edició col·laborativa en temps real. | Alumnes, escriptors, administratius i equips. |
| **Google Meet** | Plataforma de videoconferències i reunions virtuals. | Empreses, centres educatius i usuaris particulars. |
| **Google Classroom** | Gestor d'aules virtuals per assignar, lliurar i avaluar tasques acadèmiques. | Professors i estudiants de centres educatius. |

---

### 2. Diferencia entre IMAP y POP3
El protocolo IMAP sincroniza los correos directamente en el servidor, permitiendo consultar y gestionar la misma bandeja desde varios dispositivos en tiempo real. En cambio, POP3 descarga los mensajes a un único dispositivo local y, por defecto, los borra del servidor, por lo que no se mantienen sincronizados entre diferentes equipos.

### 3. Datos del mensaje original
- **SPF:** PASS (IP: 209.85.220.41)
- **DKIM:** PASS (Dominio: elpuig-xeill-net.20260707.gappssmtp.com)
- **DMARC:** PASS

**Saltos de servidor (4 servidores):**
1. Origen interno Google: `2002:a17:907:2d28:b0:c50:53cb:69fe` (03:32:09)
2. Servidor de salida Google: `mail-sor-f41.google.com` / `209.85.220.41` (03:32:09)
3. Procesamiento interno Google: `2002:a17:907:1b16:b0:c3f:7e8:235d` (03:32:10)
4. Entrega final al buzón: `2002:a05:6638:ad50:b0:620:3445:ffc7` para `laldave@elpuig.xeill.net` (03:32:10)

![Enunciado Fase 1](Captura%20desde%202026-11-19%2013-27-39.png)

### 4. Tabla de pruebas (A5.2)
| Qué pruebas | Cómo lo pruebas | Qué esperas | Qué ha pasado |
| :--- | :--- | :--- | :--- |
| 1. Acceso IMAP | Mirando la configuración de correo POP/IMAP en Gmail | Que esté activado | Está activado |
| 2. Dos sesiones | Abriendo dos ventanas con dos cuentas distintas | Poder usar las dos cuentas a la vez | Funcionan las dos a la vez sin problema |
| 3. Filtro `puig` | Enviando un correo de la cuenta A a la B con `puig` | Que llegue con la etiqueta `institut` | Ha llegado con la etiqueta `institut` |
| 4. Respuesta | Respondiendo desde la cuenta B a la A | Que la respuesta llegue a la cuenta A | Ha llegado correctamente a la cuenta A |
| 5. SPF, DKIM y DMARC | Pulsando en "Mostrar original" en el correo recibido | Que los tres pongan PASS | Los tres salen como PASS |
| 6. Servidores | Mirando las líneas `Received` en el original | Ver por cuántos servidores ha pasado | Ha pasado por 4 servidores |

---

## A5.3 - Viaje de 7 días (Google Maps y Calendar)

- **Destino:** 24 Horas de Le Mans (Francia), ida y vuelta desde Barcelona
- **Fechas:** Del 9 al 15 de julio de 2028
- **Calendario:** CALENDARI_LUCAS_ALDAVE
- **Enlace Google Maps:** (Pega aquí tu enlace de Google Maps)
- **Enlace Calendario:** [CALENDARI_LUCAS_ALDAVE](https://calendar.google.com/calendar/embed?src=laldave%40elpuig.xeill.net&ctz=Europe%2FMadrid&dates=20280709%2F20280716&mode=WEEK)

### Presupuesto (Máximo 1.500 €)
- **Vuelo ida y vuelta Barcelona – Lyon (Iberia):** 83 €
- **Hotel Lyon (Lagrange Apart'HOTEL, 2 noches):** 110 €
- **Traslados y Tren TGV París – Le Mans (ida y vuelta):** 180 €
- **Entrada Oficial Semana Completa + Grada:** 219 €
- **Hotel Le Mans (Eklo Hôtels, 5 noches a 37 €):** 185 €
- **Comidas, bebida y extras:** 280 €
- **Total:** 1.057 €
