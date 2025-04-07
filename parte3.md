# Comparativa de certificados con SSLLabs

## Detalles del certificado verídico

Para el ejemplo de certíficado verídico se ha escogido la web de Github.

El certificado es válido ya que:

![](./images/parte3/2025-04-07_11-36.png)

* Está atribuido al mismo dominio
* No ha expirado
* Tiene certificado de transparencia

![](./images/parte3/2025-04-07_11-37.png)

* Está certificado por una entidad de confianza

![](./images/parte3/2025-04-07_11-38.png)

## Detalles de los cerificados inválidos

### Certificado 1

Este cerificado no es válido ya que está expirado

![](./images/parte3/2025-04-07_11-48.png)

![](./images/parte3/2025-04-07_11-49.png)

## Certificado 2

Este cerificado no es válido ya que :

- Ocurre un error al comprobar el nombre alternativo
- El hash SHA256 con el correspondiente al certificado enviado por servidor no es válido

![](./images/parte3/2025-04-07_11-50.png)

![](./images/parte3/2025-04-07_11-51.png)

## Certificado 3

Este certificado no es válido ya que :

- No existe una cadena de confianza que certifique que es está emitido por una entidad de confianza

![](./images/parte3/2025-04-07_11-52.png)

![](./images/parte3/2025-04-07_11-52_1.png)