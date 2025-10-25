---
layout: default
title: Prime Imports SpA
nav_order: 1
description: Componentes electrónicos originales y kits técnicos para makers, técnicos y empresas en Chile.
---

# Prime Imports SpA

**Componentes electrónicos originales y kits técnicos para makers, técnicos y empresas en Chile.**

## ¿Por qué comprar con nosotros?

- ✅ **Productos 100% originales**: ESP32, sensores Bosch, ventiladores Sunon, fuentes Mean Well.
- ✅ **Factura con RUT**: respaldo fiscal para empresas y técnicos.
- ✅ **Guías técnicas en español**: código listo para usar, diagramas de conexión, soporte postventa.
- ✅ **Envíos rápidos**: Bluexpress 24–48 hrs en Santiago.

## Nuestros kits

Diseñados para resolver problemas reales: automatización de huertos, reparación de fuentes, prototipado IoT y más.

## Soporte técnico

¿Tienes dudas sobre un kit o componente?

- Para **ventas**: [ventas@primeimportsspa.cl](mailto:ventas@primeimportsspa.cl)  
- Para **soporte técnico**: [soporte@primeimportsspa.cl](mailto:soporte@primeimportsspa.cl)  
- Para **consultas generales**: [info@primeimportsspa.cl](mailto:info@primeimportsspa.cl)

## Ejemplo de código resaltado

```arduino
void setup() {
  Serial.begin(115200);
  pinMode(2, OUTPUT);
}

void loop() {
  digitalWrite(2, HIGH);
  delay(1000);
  digitalWrite(2, LOW);
  delay(1000);
}
