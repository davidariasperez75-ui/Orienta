# Herramientas

Pequeñas utilidades en HTML/JS, sin instalación ni servidor: se abren
directamente en el navegador (ordenador o móvil) y guardan los datos
localmente en ese dispositivo.

## [`seguimiento-semanal.html`](seguimiento-semanal.html)

Registro semanal de seguimiento con resumen visual y mensaje listo para
enviar a la familia.

**Cómo se usa:**
1. Abre el archivo en el navegador (doble clic, o súbelo a Google Drive y
   ábrelo con "Abrir con > Navegador").
2. En **Configuración**, define los ámbitos del caso y sus indicadores
   (uno por línea), y el objetivo mínimo de cumplimiento (60% por defecto).
   Ya viene con un ejemplo genérico de ámbitos para empezar.
3. Cada semana, marca los indicadores cumplidos y pulsa **"Generar resumen
   semanal"**. Obtienes al instante:
   - Un gráfico de cumplimiento por ámbitos (con el objetivo marcado).
   - Un gráfico de evolución del cumplimiento global semana a semana.
   - Un mensaje para la familia con los datos, la tendencia respecto a la
     semana anterior y propuestas de mejora para los ámbitos por debajo
     del objetivo.
4. Descarga los gráficos como imagen o copia el mensaje para enviarlos por
   email/WhatsApp.

**Datos e historial:**
- Todo se guarda en el navegador (localStorage), no se sube a ningún sitio.
- Puedes llevar varios "casos" a la vez (usa un alias, no el nombre real).
- "Exportar copia (JSON)" hace una copia de seguridad de todos los casos;
  "Importar copia (JSON)" la restaura (útil para cambiar de dispositivo).
- "Exportar histórico (CSV)" descarga la tabla de todas las semanas de un
  caso — útil como base para el
  [`informe de fin de curso`](../plantillas/plantilla-informe-fin-curso.md).

**Privacidad:** el archivo HTML no contiene datos de ningún alumno/a; los
datos que introduzcas quedan solo en tu navegador. Aun así, usa siempre
alias en el nombre del caso si vas a compartir el archivo o capturas de
pantalla.
