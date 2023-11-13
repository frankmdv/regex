# RegEx Exercises (PART #1):

1. Colores en formato hexadecimal:
^#([0-9A-Fa-f]{3}){1,2}$

2. Correos electrónicos:
^([a-zA-Z0-9\-\+_](\.[a-zA-Z0-9\-\+_])?)+@([a-zA-Z0-9\-\+_](\.[a-zA-Z0-9\-\+_])?)+\.[a-zA-Z]{2,}$

3. Números telefónicos con o sin extensión:
^(\(\+?[0-9]{1,3}\)\s?)?[1-9]{1}[0-9]{2}\s?[0-9]{7}$

4. Números de cedula de 10 digitos validos utilizando formato con o sin puntos:
[1-9]{1}(\.?[0-9]{3}){3}

5. URL que empiecen con https o http:
^(https|http)://([a-zA-Z0-9\-\_\+\-](\.[a-zA-Z0-9\-\_\+\-])?)*\.[a-zA-Z0-9]{2,}$

6. Tarjetas Mastercard (primer número es el 5):
^5[0-9]{3}((\s[0-9]{4}){3}|([0-9]{4}){3})$0

7. Fechas con el formato DD/MM/YYYY:
--- Acepta años de 1900 en adelante ---
^((0[1-9])|[1-2][0-9]|3[0-1])\/(0[1-9]|1[0-2])\/(19[0-9]{2}|[2-9][0-9]{3})$

--- (Versión sin barras de escape para los divisores de dia/fecha/año) ---
^((0[1-9])|[1-2][0-9]|3[0-1])/(0[1-9]|1[0-2])/(19[0-9]{2}|[2-9][0-9]{3})$

8. Direcciones IP:
^([12][0-9]{2}|[1-9][0-9]|[1-9])(\.([12][0-9][0-9]|[1-9][0-9]|[1-9])){3}$
