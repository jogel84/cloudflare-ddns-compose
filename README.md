# cloudflare-ddns-compose

El archivo usa las variables:

|  Parámetro                    |   Función                                                 |
|:------------------------------|:----------------------------------------------------------|
| TOKEN_CLOUDFLARE              | Token API de usuario generado en Cloudflare               |
| DOMINIO_CLOUDFLARE            | Dominios separados por coma que se quieren incluir        |
| TIME_CRON                     | Tiempo de ejecucion de verificación de IP, ej: @every 30s |