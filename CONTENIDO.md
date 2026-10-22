# Página: teideconsulting.com/pagar-por-transferencia

Idioma: español. Imágenes: `paso-1-destino.png`, `paso-2-importe-concepto.png`, `paso-3-cuando.png` (IBAN y referencia ya pixelados).

---

## Cómo pagar por transferencia

Al abrir el enlace de pago del presupuesto verás una tarjeta con los datos bancarios: **titular de la cuenta, BIC, IBAN, referencia y país**. Cada enlace tiene su propio IBAN y su propia referencia: usa siempre los de tu enlace, no los de estas capturas.

La transferencia se hace desde tu banco de siempre. Solo hay tres cosas que hacer bien.

### 1. Destinatario: copia el IBAN y el titular tal cual

En "nuevo destinatario" pega el IBAN y el nombre del titular exactamente como aparecen en el enlace de pago. El titular es un nombre largo (`OtoCo Base WY LLC - Teide Consulting - Series 191`): es correcto, no lo acortes ni lo "arregles". La cuenta es irlandesa (Citibank Europe), eso también es normal.

![Paso 1](paso-1-destino.png)

### 2. Importe y concepto: pon la referencia en el concepto

Escribe el importe del presupuesto y, en el campo "concepto", pega la **referencia** que te da el enlace de pago. Con esa referencia el pago se identifica solo y no hace falta que nos avises.

![Paso 2](paso-2-importe-concepto.png)

### 3. Elige transferencia ordinaria, no inmediata

Selecciona la transferencia SEPA **ordinaria** (en BBVA se llama "Puntual"; en otros bancos "estándar" o "normal"). La transferencia **inmediata o instantánea no funciona** con esta cuenta y tu banco la rechazará. La ordinaria llega el día hábil siguiente y no tiene comisión.

**Ojo: no elijas "transferencia internacional".** Aunque la cuenta sea irlandesa, está en la zona euro: se paga con la transferencia normal en euros, la misma que usas para pagar a cualquier empresa española. La opción "internacional" de tu banco es para pagos fuera de la UE y no es la que toca.

*¿Pagas desde fuera de la zona euro?* Escríbenos a info@teideconsulting.com antes de hacer nada y te indicamos la forma de pago adecuada.

![Paso 3](paso-3-cuando.png)

---

**¿Y después?** Cuando el dinero llegue, te enviamos la factura por email. Si al día hábil siguiente no has recibido nada, escríbenos a info@teideconsulting.com indicando el número de presupuesto.

---

# Texto para el email (Enviar email TC)

Pago por transferencia: en el enlace de pago encontrarás el IBAN, el titular y una referencia. Cópialos tal cual en tu banco, pon la referencia en el concepto y elige la transferencia normal en euros, ordinaria (no inmediata ni internacional). Instrucciones paso a paso con capturas: https://teideconsulting.com/pagar-por-transferencia

# Texto para el PDF del presupuesto (bloque "Forma de pago")

Transferencia normal en euros, ordinaria (no inmediata ni internacional), a los datos que aparecen en el enlace de pago. Copia IBAN, titular y referencia tal cual; la referencia va en el concepto. Instrucciones: teideconsulting.com/pagar-por-transferencia

---

# Brief para Claude Code (carpeta `~/proyectos/teide-consulting-site`)

Añade una página `/pagar-por-transferencia` con el contenido de este archivo (sección "Cómo pagar por transferencia") y las tres imágenes, reutilizando la cabecera, el pie y los estilos que ya tiene la home. Los textos de la página van en español aunque la home esté en inglés. Sustituye `info@teideconsulting.com` por el email de contacto del sitio. No enlaces la página desde el menú: se llega solo desde los presupuestos. Despliega con el mismo método que se usó para la home (revisa `wrangler.toml` / config de Pages / remote de git antes de decidir) y confírmame la URL final.
