| Símbolo | Explicación |
|---------|-------------|
| .       | Coincide con cualquier carácter excepto un salto de línea. |
| *       | Coincide con cero o más repeticiones del elemento anterior. |
| +       | Coincide con una o más repeticiones del elemento anterior. |
| ?       | Coincide con cero o una repetición del elemento anterior. |
| ^       | Coincide con el inicio de una cadena. |
| $       | Coincide con el final de una cadena. |
| [...]   | Coincide con cualquier carácter dentro de los corchetes. |
| [^...]  | Coincide con cualquier carácter que no esté dentro de los corchetes. |
| \       | Escapa el siguiente carácter especial. |
| \d      | Coincide con un dígito. |
| \w      | Coincide con un carácter alfanumérico o un guión bajo. |
| \s      | Coincide con un espacio en blanco. |

Ejemplos:

- La expresión regular ```a.c``` coincidiría con "abc", "adc", "aec", etc., pero no con "ac" ni "abbc".
- La expresión regular ```ab*c``` coincidiría con "ac", "abc", "abbc", etc.
- La expresión regular ```ab+c``` coincidiría con "abc", "abbc", "abbbc", etc., pero no con "ac".
- La expresión regular ```ab?c``` coincidiría con "ac" y "abc", pero no con "abbc" ni "abbbc".
- La expresión regular ```^abc``` coincidiría con "abc" al inicio de una cadena.
- La expresión regular ```abc$``` coincidiría con "abc" al final de una cadena.
- La expresión regular ```[aeiou]``` coincidiría con cualquier vocal.
- La expresión regular ```[^aeiou]``` coincidiría con cualquier consonante.
- La expresión regular ```\d\d\d``` coincidiría con cualquier secuencia de tres dígitos.
- La expresión regular ```\w+``` coincidiría con cualquier palabra o secuencia de caracteres alfanuméricos.
- La expresión regular ```\s\s\s``` coincidiría con cualquier secuencia de tres espacios en blanco.