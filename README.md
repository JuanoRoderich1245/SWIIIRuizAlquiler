# SWIIIRuizAlquiler
DOMINIO CORE:
- Gestión de Alquileres (Reservas, estado, disponibilidad y contratos)
- Gestión de Vehículos (Mantenimiento, características y disponibilidad, historial)
SUBDOMINIO DE APOYO:
- Gestión de Clientes (Cuentas turistas, información cliente)
- Gestión de Pagos (Pagos, Facturas y recibo transacción)
SUBDOMINIO GENÉRICO:
- Seguridad (Autenticación y Autorización, Políticas y Protocolos de seguridad)

  En el Context Mapper se encontrron los siguientes patrones:
  - Seguridad Context tendrá el Parteship con los demás Bounded Context debido que cada uno presenta protocolos de seguridad a nivel general y cuidando los datos de ellos.
  - Gestión de Alquiler tendrá en común con Gestión de Vehículos y ambos son core.
