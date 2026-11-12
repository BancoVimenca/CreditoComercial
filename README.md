# Crédito Comercial - Banco Vimenca

Repositorio oficial bajo arquitectura **Salesforce DX (Source Format)** gobernado por **KeyHub & Keystone Context Engine**.

## 🏗️ Estructura del Repositorio
- `force-app/main/default/`: Metadatos de Salesforce (Apex Classes, Triggers, LWC, Custom Objects, Layouts).
- `manifest/package.xml`: Manifiesto de despliegue y homologación de componentes.
- `sfdx-project.json`: Configuración del proyecto Salesforce DX.

## 🚀 Ambientes Oficiales
- **DEV**: `vimenca--mergeqa.sandbox.my.salesforce.com` (Rama `develop`)
- **QA**: `vimenca--calidad.sandbox.my.salesforce.com` (Rama `qa`)
- **PROD**: `vimenca.my.salesforce.com` (Rama `main` - Protegida)
