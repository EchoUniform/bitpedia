# Servicios DNS

## Diferencias entre DNS estático y dinámico

El [DNS](https://es.wikipedia.org/wiki/Sistema_de_nombres_de_dominio) estático se usa cuando las [direcciones IP](https://es.wikipedia.org/wiki/Direcci%C3%B3n_IP) son fijas o se gestionan [dominios](https://es.wikipedia.org/wiki/Dominio_de_internet) completos, como suele ocurrir en [sitios web](https://es.wikipedia.org/wiki/Sitio_web) o [servidores](https://es.wikipedia.org/wiki/Servidor) con configuración estable.

El [DNS](https://es.wikipedia.org/wiki/Sistema_de_nombres_de_dominio) dinámico es útil cuando la [conexión a Internet](https://es.wikipedia.org/wiki/Conexi%C3%B3n_a_Internet) cambia de [IP](https://es.wikipedia.org/wiki/Direcci%C3%B3n_IP) frecuentemente como ocurre en la mayoría de las [conexiones](https://es.wikipedia.org/wiki/Conexi%C3%B3n_a_Internet) domésticas. Permite que el [dominio](https://es.wikipedia.org/wiki/Dominio_de_internet) siga apuntando correctamente sin intervención manual, cada vez que cambia la [IP](https://es.wikipedia.org/wiki/Direcci%C3%B3n_IP) pública.

## Servicios DNS estático

* [deSEC](https://desec.io/) - Un servicio [DNS](https://es.wikipedia.org/wiki/Sistema_de_nombres_de_dominio) gratuito con una API REST completa

  **Ventajas principales**:

    - Completamente gratuito y sin publicidad

    - Registro rápido solo con [correo electrónico](https://es.wikipedia.org/wiki/Correo_electr%C3%B3nico) (sin pedir nombre, dirección u otros datos personales)

    - [API](https://es.wikipedia.org/wiki/API) robusta para gestionar y modificar registros [DNS](https://es.wikipedia.org/wiki/Sistema_de_nombres_de_dominio) fácilmente

    - Soporte para [IPv4](https://es.wikipedia.org/wiki/IPv4) e [IPv6](https://es.wikipedia.org/wiki/IPv6)

    - Compatibilidad con [DNSSEC](https://es.wikipedia.org/wiki/Domain_Name_System_Security_Extensions) para mayor seguridad

    - Función de [DNS](https://es.wikipedia.org/wiki/Sistema_de_nombres_de_dominio) branding para personalización de [dominios](https://es.wikipedia.org/wiki/Dominio_de_internet)

  **Desventaja principal**:

    - No ofrece reenvío de [correo electrónico](https://es.wikipedia.org/wiki/Correo_electr%C3%B3nico) ni [servicio web](https://es.wikipedia.org/wiki/Servicio_web)

## Servicios DNS dinámico
  
* [FreeMyIP](https://freemyip.com) – [DNS](https://es.wikipedia.org/wiki/Sistema_de_nombres_de_dominio) dinámico gratuito y sin registro

  **Ventajas principales**:

    - Completamente gratuito y sin publicidad

    - No requiere registro (no solicita ni [correo electrónico](https://es.wikipedia.org/wiki/Correo_electr%C3%B3nico))

    - [API](https://es.wikipedia.org/wiki/API) compatible con `curl`, `wget` y [DDNS](https://es.wikipedia.org/wiki/Sistema_de_nombres_de_dominio) comunes

    - Soporte para [IPv4](https://es.wikipedia.org/wiki/IPv4) e [IPv6](https://es.wikipedia.org/wiki/IPv6)

    - Ideal para [scripts](https://es.wikipedia.org/wiki/Script), dispositivos caseros y [servidores](https://es.wikipedia.org/wiki/Servidor) personales

  **Desventajas**:

    - Solo se pueden usar [subdominios](https://es.wikipedia.org/wiki/Dominio_de_internet) bajo `freemyip.com`

    - No ofrece soporte para [DNSSEC](https://es.wikipedia.org/wiki/Domain_Name_System_Security_Extensions)

## Herramientas para análisis y verificación

* [DNS Checker](https://dnschecker.org/) - Muestra la propagación de cualquier tipo de registro DNS (A, AAAA, MX, TXT, NS, etcétera) desde decenas de localizaciones

* [Verisign DNSSEC Analyzer](https://dnssec-analyzer.verisignlabs.com/) – Permite comprobar si la configuración [DNSSEC](https://es.wikipedia.org/wiki/Domain_Name_System_Security_Extensions) de un [dominio](https://es.wikipedia.org/wiki/Dominio_de_internet) está correctamente implementada y funcionando. Muy útil para verificar que los registros se han propagado y que la cadena de confianza es válida.

* [DMARC Inspector](https://dmarcian.com/dmarc-inspector/) - Analiza los registros [DMARC](https://es.wikipedia.org/wiki/DMARC) de un [dominio](https://es.wikipedia.org/wiki/Dominio_de_internet)

* [Newsletters spam test](https://www.mail-tester.com/) - Se envía un correo a una dirección temporal que se proporciona y devuelven un análisis completo: [DKIM](https://es.wikipedia.org/wiki/DomainKeys_Identified_Mail), [SPF](https://es.wikipedia.org/wiki/Sender_Policy_Framework), [DMARC](https://es.wikipedia.org/wiki/DMARC), reputación, etcétera
