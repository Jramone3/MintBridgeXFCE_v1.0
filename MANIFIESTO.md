# 📘 MANIFIESTO – MintBridge XFCE v1.0

Este manifiesto documenta el estado técnico, propósito, trazabilidad y condiciones de distribución del toolkit MintBridge XFCE v1.0.

---

## 🧱 Identificación técnica

- Nombre del paquete: `MintBridgeXFCE_v1.0`
- Autor técnico: `jramonrivasg`
- Fecha de cierre: `2025-09-18`
- Clave usada: `MintBridgeTurmero@2025`
- Fingerprint: `E977 3AC8 CC13 9199 7D16 B9C4 7DF4 7476 5A2B 878F`

---

## 📦 Componentes incluidos

- `MintBridge.html` (versión bilingüe validada)
- `README.md` (documentación técnica)
- `firma_index.md` (índice técnico consolidado)
- `checksums.sha256` (registro de hash)
- `MintBridgeXFCE_v1.0.tar.gz` (paquete comprimido)
- `MintBridgeXFCE_v1.0.tar.gz.sig` (firma digital)

---

## 🔐 Validación técnica

Todos los archivos críticos están firmados digitalmente y trazados bajo el estándar jramonrivasg.  
Verificación:

```bash
gpg --verify MintBridgeXFCE_v1.0.tar.gz.sig MintBridgeXFCE_v1.0.tar.gz
sha256sum -c checksums.sha256
