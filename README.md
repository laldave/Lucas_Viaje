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

https://docs.google.com/document/d/1nIOFQVvRgHa-kPrlXNWAYicLxtT7HF6pouiO_5Q6MAw/edit?usp=sharing

A5.2

### 1.Diferencia de IMAP y POP con mis palabras
- IMAP sincroniza los correos directamente con el servidor, permitiendo ver los mensajes y cambios en tiempo real desde varios dispositivos a la vez. En cambio, POP3 descarga los correos en un único dispositivo local y, por defecto, los borra del servidor.

2.Datos del mensaje original
- **SPF:** PASS (IP: de google)
- **DKIM:** PASS (Dominio: elpuig.xeill.net)
- **DMARC:** PASS

### 2. Tabla de pruebas (A5.2)
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
- **Enlace Google Maps:** [google maps](https://www.google.com/maps/dir/Barcelona/Lagrange+apart'HOTEL+-+Lyon+Lumi%C3%A8re,+81-85+Cr+Albert+Thomas,+69003+Lyon,+Francia/Par%C3%ADs,+Francia/Eklo+H%C3%B4tels+Le+Mans,+34+Rue+Louis+de+Broglie,+72000+Le+Mans,+Francia/Circuito+de+la+Sarthe,+Pl.+Luigi+Chinetti,+72019+Le+Mans,+Francia/Par%C3%ADs,+Francia/Lyon,+Francia/Barcelona/@44.9719851,2.6983999,6.58z/data=!4m49!4m48!1m5!1m1!1s0x12a49816718e30e5:0x44b0fb3d4f47660a!2m2!1d2.1686496!2d41.3874374!1m5!1m1!1s0x47f4ea75861f68eb:0xf7ca86fc95786b4!2m2!1d4.868867!2d45.7465143!1m5!1m1!1s0x47e66e1f06e2b70f:0x40b82c3688c9460!2m2!1d2.3513765!2d48.8575475!1m5!1m1!1s0x47e28615246f63eb:0xe1f68e93886e81d0!2m2!1d0.1451013!2d48.0177274!1m5!1m1!1s0x47e28fad5242c195:0xe9ae326c6c02c174!2m2!1d0.2079771!2d47.9559971!1m5!1m1!1s0x47e66e1f06e2b70f:0x40b82c3688c9460!2m2!1d2.3513765!2d48.8575475!1m5!1m1!1s0x47f4ea516ae88797:0x408ab2ae4bb21f0!2m2!1d4.835659!2d45.764043!1m5!1m1!1s0x12a49816718e30e5:0x44b0fb3d4f47660a!2m2!1d2.1686496!2d41.3874374?entry=ttu&g_ep=EgoyMDI2MTEyMi4wIKXMDSoASAFQAw%3D%3D)
- **Enlace Calendario:** [CALENDARI_LUCAS_ALDAVE](https://calendar.google.com/calendar/embed?src=laldave%40elpuig.xeill.net&ctz=Europe%2FMadrid&dates=20280709%2F20280716&mode=WEEK)

### Presupuesto (Máximo 1.500 €)
- [Presupuesto viaje](https://docs.google.com/spreadsheets/d/15ZpR5sizKqRl2Q-32NgbJl5P0Q300DZPodX3to7W_GE/edit?usp=sharing)
