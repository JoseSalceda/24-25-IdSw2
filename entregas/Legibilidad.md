# Revisión de código antiguo y Mejora de Malas Prácticas

## 1. Errores de Formato

**Mal identado** [Link](https://github.com/JoseSalceda/prg1-22-23/blob/1d9b1cca2a63df66b88dcc1b8838202ecd9bbf29/retos/entregas/JoseSalceda/CCCF-ElAlisal/CCCF2-RetoExtendido.java#L23)

**La llave de cierre no está bien alineada con el resto del código.** [Link](https://github.com/JoseSalceda/prg1-22-23/blob/1d9b1cca2a63df66b88dcc1b8838202ecd9bbf29/retos/entregas/JoseSalceda/ElCaracol/CaracolRetoExtendido#L86)

## 2. Uso de Nombres de forma inconsistente (Mejora en el nombrado)

**Inconsistencia en el nombrado de variables. Algunas usan camelCase y otras no (ejemplo: "VidaCaracol" vs "distanciaSubida").** [Link](https://github.com/JoseSalceda/prg1-22-23/blob/1d9b1cca2a63df66b88dcc1b8838202ecd9bbf29/retos/entregas/JoseSalceda/ElCaracol/CaracolRetoExtendido#L4)   

## 3. Comentarios

**0 comentarios** [Link](https://github.com/JoseSalceda/prg1-22-23/blob/1d9b1cca2a63df66b88dcc1b8838202ecd9bbf29/retos/entregas/JoseSalceda/CCCF-ElAlisal/CCCF2-RetoExtendido.java)

## 4. Estándares



## 5. Consistencia

**Se usa "prob1" pero en otras partes se usa "cant" para variables de propósito similar.** [Link](https://github.com/JoseSalceda/prg1-22-23/blob/1d9b1cca2a63df66b88dcc1b8838202ecd9bbf29/retos/entregas/JoseSalceda/CCCF-ElAlisal/CCCF2-RetoExtendido.java#L15)

## 6. Alertas

**Las variables distanciaSubida y distanciaCaida se declaran dentro de los bloques condicionales pero no se inicializan para el caso donde ninguno de los condicionales se cumpla.** [Link](https://github.com/JoseSalceda/prg1-22-23/blob/1d9b1cca2a63df66b88dcc1b8838202ecd9bbf29/retos/entregas/JoseSalceda/ElCaracol/CaracolRetoExtendido#L10)

## 7. Código Muerto



## 8. YAGNI (You aren’t going to need it)



## 9. DRY (Don’t repeat yourself)

**El código para procesar cada caja es casi idéntico. Se repite cuatro veces la misma lógica.** [Link](https://github.com/JoseSalceda/prg1-22-23/blob/1d9b1cca2a63df66b88dcc1b8838202ecd9bbf29/retos/entregas/JoseSalceda/CCCF-ElAlisal/CCCF2-RetoExtendido.java#L31)

**Los bloques de impresión son casi idénticos con mínimas diferencias.** [Link](https://github.com/JoseSalceda/prg1-22-23/blob/1d9b1cca2a63df66b88dcc1b8838202ecd9bbf29/retos/entregas/JoseSalceda/CCCF-ElAlisal/CCCF2-RetoExtendido.java#L83)