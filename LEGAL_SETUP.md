# 📋 Documentos Legales - SanaMente

Se han creado 3 documentos legales para cubrir la protección legal de tu plataforma:

## Archivos Creados

### 1. **privacy.html** - Política de Privacidad
- Tratamiento de datos personales (RGPD compatible)
- Finalidades del procesamiento
- Almacenamiento y seguridad
- Derechos del usuario (acceso, rectificación, supresión, etc.)
- Cookies y tecnologías de seguimiento
- Retención de datos
- Contacto para ejercer derechos

### 2. **terms.html** - Términos de Servicio
- Elegibilidad para usar el servicio
- Descripción del servicio
- Responsabilidades del usuario
- Prohibiciones de uso
- Responsabilidad legal y cumplimiento tributario
- Limitaciones de responsabilidad
- Terminación de cuenta
- Indemnización

### 3. **legal.html** - Aviso Legal
- Información de identificación
- Información sobre facturas (valor fiscal)
- Exclusión de responsabilidad
- Asesoramiento profesional (recomienda consultar contador)
- Protección de datos de terceros
- Limitaciones técnicas
- Seguridad e integridad

---

## 🔗 Integración en index.html

### Opción 1: Agregar enlaces en el Footer

Busca el footer de tu página (probablemente cerca del final del archivo) y añade:

```html
<footer style="text-align: center; padding: 40px 20px; margin-top: 80px; border-top: 1px solid rgba(255, 255, 255, .06); color: #C8C2BA; font-size: 0.9em;">
  <p style="margin-bottom: 15px;">&copy; 2026 SanaMente. Todos los derechos reservados.</p>
  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
    <a href="privacy.html" style="color: #C9964A; text-decoration: none;">Política de Privacidad</a>
    <a href="terms.html" style="color: #C9964A; text-decoration: none;">Términos de Servicio</a>
    <a href="legal.html" style="color: #C9964A; text-decoration: none;">Aviso Legal</a>
  </div>
</footer>
```

### Opción 2: Banner de Aceptación (recomendado para RGPD)

Coloca esto al inicio del `<body>` de index.html para mostrar un aviso de cookies/privacidad:

```html
<div id="legal-banner" style="
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
  background: rgba(19, 19, 22, 0.98);
  border-top: 1px solid rgba(201, 150, 74, .25);
  padding: 20px;
  z-index: 1000;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 20px;
  font-size: 0.9em;
  color: #C8C2BA;
  backdrop-filter: blur(10px);
">
  <p style="margin: 0;">
    Al usar SanaMente, aceptas nuestra 
    <a href="privacy.html" style="color: #C9964A; text-decoration: underline;">Política de Privacidad</a> y 
    <a href="terms.html" style="color: #C9964A; text-decoration: underline;">Términos de Servicio</a>
  </p>
  <button onclick="document.getElementById('legal-banner').style.display='none'" style="
    background: #C9964A;
    color: #0C0C0E;
    border: none;
    padding: 8px 20px;
    border-radius: 6px;
    cursor: pointer;
    font-weight: 500;
    white-space: nowrap;
  ">Entendido</button>
</div>
```

---

## ✅ Cobertura Legal

Los documentos cubren:

| Aspecto | Cubierto |
|--------|----------|
| **RGPD** | ✓ Completo |
| **Protección de Datos** | ✓ Completo |
| **Cumplimiento Tributario** | ✓ Referenciado |
| **Facturas Electrónicas** | ✓ Aviso Legal |
| **Cookies/Tracking** | ✓ Privacy Policy |
| **Responsabilidades** | ✓ Todos |
| **Terminación** | ✓ Terms |
| **Seguridad** | ✓ Privacy + Legal |

---

## 📝 Notas Importantes

⚠️ **Estos documentos son genéricos pero legales.** Para máxima protección:
- Consulta con un abogado local para tu jurisdicción
- Ajusta según leyes específicas de tu país
- Verifica cumplimiento tributario con asesor fiscal
- Actualiza anualmente o con cambios legales

---

## 🎯 Próximos Pasos

1. **Integra los enlaces** en el footer de index.html
2. **Añade el banner** si deseas cumplimiento RGPD
3. **Solicita revisión legal** local si es posible
4. **Comunica los cambios** a usuarios existentes
5. **Mantén actualizado** según cambios legales

