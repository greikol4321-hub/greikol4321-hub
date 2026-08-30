<p align="center">
  <img src="./assets/readme/hero.svg" width="100%" alt="Greikol — software útil para colegios y negocios">
</p>

Soy de Quepos y me gusta hacer cosas que la gente pueda usar sin enredos. La verdad es que prefiero un sistema pequeño que funciona todos los días a una idea grande que nunca sale, por eso casi todo lo que publico ya está corriendo en algún colegio o negocio de por acá.

Al fin y al cabo, si nadie lo abre, no sirve de mucho. Eso sí, intento que lo que hago se entienda rápido, que no pida manual y que no dependa de cosas raras para pagar o validar.

### En qué ando

**Entradas CTPM** es el que más se ha movido. Es la venta para el Gran Baile del CTP Matapalo. La gente paga con SINPE Móvil, sube la captura y el sistema le genera una entrada con QR. Ese QR se escanea en puerta y queda marcado, no hay forma de usarlo dos veces. El detalle que más costó fue el gimnasio. No es un dibujo genérico. Son 12 mesas tal cual están, cada una con sus seis sillas, y si una está ocupada nadie más la puede tomar. Todo eso está con Flask, Supabase para base y storage, y Vercel para que cargue rápido. El QR se arma con Pillow y qrcode, y la validación queda con estados simples que cualquiera del equipo entiende.

Luego está **Jungle Wildlife Tours**. Ahí el tema era otro. Un grupo de guías quería una web que no pareciera de plantilla. Fotos de verdad de la selva, texto sin vueltas y un panel donde ellos mismos cambian precios y fechas. Sin ir más lejos, lo armamos con Astro y Next.js, Tailwind para que se vea limpio en el celular y Supabase detrás para las reservas. Nada del otro mundo, pero funciona y ellos lo pueden tocar sin llamarme.

Y **Notificaciones CTP Quepos** nació del caos de WhatsApp. Los avisos se perdían entre audios y stickers. Entonces hicimos algo aparte. Un lugar donde la dirección publica, le llega a padres y estudiantes y queda el registro. Está con TypeScript adelante y Flask atrás, sin mucho adorno pero con lo justo para que no se vuelva a perder nada.

Si te sirve alguno, lo ves corriendo:

- Entradas CTPM → [entradas-ctpm.vercel.app](https://entradas-ctpm.vercel.app) · [código](https://github.com/greikol4321-hub/entradas-ctpm) — Flask, Supabase, Vercel, QR
- Jungle Wildlife Tours → [jungle-wildlife-tours.vercel.app](https://jungle-wildlife-tours.vercel.app) · [código](https://github.com/greikol4321-hub/jungle-wildlife-tours) — Astro, Next.js, Tailwind, TypeScript
- Notificaciones CTP → [código](https://github.com/greikol4321-hub/Notificaciones-CTP-De-Quepos) — TypeScript, Flask

### Cómo me gusta trabajar

No me complico. Si hay 12 mesas, dibujo 12. Si la gente paga con SINPE, uso SINPE. El QR es de un solo uso y punto. Y el panel tiene que leerse sin curso. Pendiente, aprobada, usada y finanzas por zona. Lo demás es ruido. Mira, prefiero que me digas qué sobra a que me falte algo que sí usa alguien.

### Con qué lo armo

No es por la herramienta, es porque ya lo probé y no me dio problemas. Flask, Supabase con Postgres y Storage, Vercel, Astro, Next.js, Tailwind, TypeScript y Python. Para los QR uso Pillow y qrcode, para la base psycopg y para validar datos pydantic. Vamos, lo normal.

Si algo de esto te ayuda para tu colegio o negocio, escríbeme y lo vemos. Y si no, también.

<p align="center">
  <a href="https://entradas-ctpm.vercel.app">entradas-ctpm</a> · <a href="https://jungle-wildlife-tours.vercel.app">jungle</a> · Quepos, Costa Rica
</p>
