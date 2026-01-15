# Prensa Mecanica - Proyecto CAD

## Descripcion General

Proyecto de diseno mecanico de una prensa de banco desarrollado en SolidWorks. El ensamblaje incluye todos los componentes necesarios para el funcionamiento completo del mecanismo de sujecion.

## Estructura del Proyecto

### Componentes Principales

| No. | Componente | Archivo de Pieza | Archivo de Dibujo |
|-----|------------|------------------|-------------------|
| 01 | Base | 01_Base.SLDPRT | 01_Base.SLDDRW |
| 02 | Mordaza | 02_Mordaza.SLDPRT | 02_Mordaza.SLDDRW |
| 03 | Placa Mordaza | 03_Placa_Mordaza.SLDPRT | 03_Placa_Mordaza.SLDDRW |
| 04 | Tornillo Prensa | 04_Tornillo_Prensa.SLDPRT | 04_Tornillo_Prensa.SLDDRW |
| 05 | Collarin | 05_Collarin.SLDPRT | 05_Collarin.SLDDRW |
| 06 | Cuna Especial | 06_Cuña_Especial.SLDPRT | 06_Cuña_Especial.SLDDRW |
| 07 | Varilla Manivela | 07_Varilla_Manibela.SLDPRT | 07_Varilla_Manibela.SLDDRW |
| 08 | Esfera | 08_Esfera.SLDPRT | 08_Esfera.SLDDRW |
| 09 | Cuna Corredera | 09_Cuña_Corredera.SLDPRT | 09_Cuña_Corredera.SLDDRW |
| 10 | Prisionero | 10_Prisionero.SLDPRT | 10_Prisionero.SLDDRW |
| 11 | Perno | 11_Perno.SLDPRT | 11_Perno.SLDDRW |

### Variantes

- `09_Cuña_Corredera - Inversa.SLDPRT`: Version espejada de la cuna corredera

### Ensamblajes

| Ensamblaje | Archivo | Dibujo Tecnico |
|------------|---------|----------------|
| Manija | Ensamblaje_Manija.SLDASM | Ensamblaje_Manija.SLDDRW |

## Tipos de Archivo

- `.SLDPRT` - Archivos de pieza (Part) de SolidWorks
- `.SLDDRW` - Archivos de dibujo tecnico (Drawing) de SolidWorks
- `.SLDASM` - Archivos de ensamblaje (Assembly) de SolidWorks

## Requisitos de Software

- SolidWorks 2020 o superior
- Licencia activa de SolidWorks para edicion de archivos

## Descripcion de Componentes

### Base (01)
Estructura principal que soporta el mecanismo de la prensa y proporciona estabilidad al conjunto.

### Mordaza (02)
Elemento movil que realiza la funcion de sujecion junto con la placa mordaza.

### Placa Mordaza (03)
Superficie de contacto con la pieza de trabajo.

### Tornillo Prensa (04)
Husillo roscado que transmite el movimiento rotacional en movimiento lineal para accionar la mordaza.

### Collarin (05)
Elemento de retencion axial del tornillo.

### Cuna Especial (06)
Componente de guia y posicionamiento.

### Varilla Manivela (07)
Elemento de accionamiento manual del mecanismo.

### Esfera (08)
Elemento terminal de la manivela para ergonomia de operacion.

### Cuna Corredera (09)
Guia de deslizamiento para el movimiento lineal de la mordaza.

### Prisionero (10)
Tornillo de fijacion para asegurar componentes.

### Perno (11)
Elemento de union y pivote.

## Notas Tecnicas

- Los archivos de dibujo (.SLDDRW) contienen vistas ortogonales, dimensiones y tolerancias
- El ensamblaje principal referencia todas las piezas individuales
- Respetar la numeracion de piezas para trazabilidad

## Autor

Ing. Karen lesmes

---
