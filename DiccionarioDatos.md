
# Diccionario de datos

## Diccionario de datos 

| Nombre de la variable | Tipo     | Descripción                | Valores Validos | Relevancia |
| :-------- | :-------------------------  | :-------- | :-------------------------  |:---------  |
| `TARIFA_PS` | `Categorica` | Plan de Internet | Revisar **mapeo tarifas** | Alta |
| `ESTADO_SUMINISTRO` | `Categorica` | Estado del suministro de internet del cliente | 0 - Con Suministro, 2 - Suspendido, 52 - Retirado | Alta |
| `DEUDA` | `Numerica` | Deuda acumulada del cliente | **Numeros enteros** | Alta |
| `ANTIGUEDAD_SALDO` | `Numerica` | Numero de meses atrasados | **Numeros naturales** | Alta |
| `DEPTO` | `Categorica` | Departamento | Tolima, Valle del Cauca | Alta |
| `MUNICIPIO` | `Categorica` | Municipios del Valle y del Tolima |  | Alta |
| `BARRIO` | `Categorica` | Barrios del Valle y del Tolima |  | Alta |
| `ESTRATO` | `Categorica` | Estrato de la vivienda |  | Alta |
| `CLASE_SERVICIO` | `Categorica` | Tipo de servicio | Residencial, Comercial  | Media |
| `CLIENTE_ID` | `Categorica` | ID del cliente | d91b230b-8619-53e2-8772-52cc8ce140be | Baja | 
| `ESTADO_CLIENTE` | `Categorica` | Estado del cliente | 0-Activo, 30-Inactivo| Baja |
| `ESTADO_FACTURACION` | `Categorica` | Estado de la factura del mes | 0-Sin Proceso, 2- Calculo de Consumo | Media |
| `FECHA_VENCIMIENTO` | `Categorica` | Fecha de vencimiento |  | Media |
| `TOTAL_FACTURADO` | `Numerica` | Total facturado en ese mes | **Numeros Enteros** | Media|
| `GRUPO_CU` | `Categorica` | Grupo de clientes | Valle, Tolima | Baja |
| `CICLO` | `Categorica` | Numero de ciclo de facturación |  | Baja | 
| `ZONA` | `Categorica` | Zona en el municipio |  | Baja |
| `TIPO_SERVICIO` | `Categorica` | Telecomunicaciones | Telecomunicaciones | Baja |
| `FECHA_FACTURACION` | `Categorica` | Fecha de facturación en el mes |  | Baja |
| `FECHA_ULT_PAGO` | `Categorica` | Fecha del ultimo pago |  | Baja | 
| `VALOR_ULT_PAGO` | `Categorica` | Valor del ultimo pago | **Numeros Enteros** | Baja | 


#### Mapeo de tarifas
| Código | Nombre del Paquete |
|--------|---------------------|
| 389 | PAQUETE 100 MEGAS 2025 |
| 312 | PAQUETE 200 MEGAS 2024 |
| 313 | PAQUETE 400 MEGAS 2024 |
| 311 | PAQUETE 100 MEGAS 2024 |
| 390 | PAQUETE 200 MEGAS 2025 |
| 302 | PAQUETE 200 MEGAS 2023 |
| 320 | PAQUETE 50 MEGAS PARA FIDELIDAD |
| 321 | PAQUETE 100 MEGAS 2022 |
| 391 | PAQUETE 400 MEGAS 2025 |
| 301 | PAQUETE 100 MEGAS 2023 |
| 324 | PAQUETE 200 MEGAS 2023 V |
| 323 | PAQUETE 100 MEGAS BETA 2022 |
| 303 | PAQUETE 400 MEGAS 2023 |
| 392 | PAQUETE 600 MEGAS 2025 |
| 713 | PAQUETE 200 + HULU GOLD 2023 |
| 314 | PAQUETE 600 MEGAS 2024 |
| 398 | PAQUETE 600 MEGAS 2025 NV |
| 741 | PAQUETE 200 + HULU SILVER + ESPN 2024 |
| 743 | PAQUETE 200 + HULU GOLD 2024 |
| 325 | PAQUETE 200 MEGAS BETA |
| 326 | PAQUETE 25 MEGAS PA |
| 304 | PAQUETE 600 MEGAS 2023 |
| 334 | PAQUETE 600 MEGAS 2023-01 V |
| 329 | PAQUETE 400 MEGAS 2022 V |
| 397 | PAQUETE 300 MEGAS 2025 NV |
| 330 | PAQUETE 400 MEGAS BETA |
| 337 | PAQUETE 50 MEGAS 2022 V |
| 336 | PAQUETE 25 MEGAS |
| 739 | PAQUETE 200 + HULU SILVER 2024 |
| 731 | PAQUETE 100 + HULU SILVER 2024 |
| 715 | PAQUETE 200 + HULU GOLD + ESPN 2023 |
| 332 | PAQUETE 50 MEGAS BETA 2022 V |
| 331 | PAQUETE 50 MEGAS PA 2022 V |
| 322 | PAQUETE 100 MEGAS PA 2022 |
| 703 | PAQUETE 100 + HULU SILVER + ESPN 2023 |
| 394 | PAQUETE 300 MEGAS DELTA 2025 |
| 733 | PAQUETE 100 + HULU SILVER + ESPN 2024 |
| 701 | PAQUETE 100 + HULU SILVER 2023 |
| 801 | PAQUETE GRATIS 100 MEGAS |
| 709 | PAQUETE 200 + HULU SILVER 2023 |
| 333 | PAQUETE 600 MEGAS DELTA |
| 803 | PAQUETE GRATIS 100 MEGAS 2025 |
| 395 | PAQUETE 600 MEGAS DELTA 2025 |
| 714 | PAQUETE 200 + HULU GOLD + HBO 2023 |
| 802 | PAQUETE ESCOLARIZACION 500 MEGAS |
| 724 | PAQUETE 400 + HULU GOLD + HBO + ESPN 2023 |
| 328 | PAQUETE 300 MEGAS PA |
| 752 | PAQUETE 400 + HULU GOLD + HBO 2024 |
| 396 | PAQUETE 800 MEGAS 2025 |
| 745 | PAQUETE 200 + HULU GOLD + ESPN 2024 |
| 754 | PAQUETE 400 + HULU GOLD + HBO + ESPN 2024 |
| 722 | PAQUETE 400 + HULU GOLD + HBO 2023 |
| 763 | PAQUETE 200 + HULU SILVER 2025 |
| 327 | PAQUETE 300 MEGAS DELTA |
| 767 | PAQUETE 200 + HULU GOLD 2025 |
| 717 | PAQUETE 400 + HULU SILVER 2023 |
| 335 | PAQUETE CORPORATIVO |
| 757 | PAQUETE 100 + HULU SILVER + ESPN 2025 |
| 755 | PAQUETE 100 + HULU SILVER 2025 |
| 747 | PAQUETE 400 + HULU SILVER 2024 |
| 299 | TARIFA SIN CONCEPTOS |
| 305 | PAQUETE 600 PLUS MEGAS 2023 |
| 339 | PAQUETE 400 NEON MEGAS |
| 338 | PAQUETE 200 NEON MEGAS |
| 340 | PAQUETE 600 NEON MEGAS |






