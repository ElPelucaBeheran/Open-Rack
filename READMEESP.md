# Open-Rack

![Vista previa de Open Rack](images/preview.png)

Open Rack es un **sistema de rack personalizado de 300 mm** que utiliza medidas simples y fáciles de recordar.
Está diseñado para utilizar **únicamente tornillos M4**, permitiendo montar el hardware sin necesidad de tuercas.

---

## 📦 Descripción del sistema

![Unidad Completa](images/full-unit.png)

![Unidad Completa IRL](images/IRL/total-assembly.png)

El sistema está compuesto por **dos unidades diferentes**:

---

### 🔲 Unidad Completa (300 mm de ancho)

![RACK de 300](images/300-unit.png)
![RACK de 300 IRL](images/IRL/full-u.png)

**Medidas**

* **RACK**
  -- ![Diagrama RACK de Unidad Completa](images/300-u-diagram.png)

* **UNIT**
  -- ![Diagrama de Unidad Completa](images/full-u-diagram.png)
  Esta unidad permite:

* Instalar **placas madre M-ATX**

* Montar hasta **2 × discos duros SATA de 3,5"/2,5" por bahía**

---

### 🔳 Media Unidad (150 mm de ancho)

![Media Unidad](images/half-unit.png)
![Media Unidad IRL](images/IRL/half-u.png)

**Medidas**

* **RACK**
  ![Media Unidad](images/half-udiagram.png)

* **UNIT**
  ![Diagrama de Media Unidad Completa](images/half-u-diagram.png)
  Esta unidad está diseñada para alojar:

* **Computadoras de placa única** (por ejemplo, Raspberry Pi)

* Componentes más pequeños, como:

  * Fuentes de alimentación ATX
  * Módulos LCD I2C
  * Equipos de red

---

## 🛠️ Montaje

Cómo unir la Unidad Completa y la Media Unidad en una sola
[▶️](https://www.youtube.com/watch?v=qaGLMwjam0k)

![Video del montaje](images/Assembly-Video.gif)

### 🔲 Unidad Completa

#### STLs

[3D-Models/STLs/Full-Unit](https://github.com/ElPelucaBeheran/Open-Rack/tree/main/3D-Models/STLs/Full-Unit)

* Columnas ×4
* Full-U Base A ×1
* Full-U Base B ×1
* Full-U Top A ×1
* Full-U Top B ×1
* Full-U Grid A ×1
* Full-U Grid B ×1
* Side Grid ×2

#### Herrajes

* Tuerca M4 ×12
* Tornillo M4 × 20 mm ×12
* Tornillo M4 × 10 mm ×4

---

### 🔳 Media Unidad

#### STLs

[3D-Models/STLs/Half-Unit](https://github.com/ElPelucaBeheran/Open-Rack/tree/main/3D-Models/STLs/Half-Unit)

* Columnas ×4
* Half-U Base A ×1
* Half-U Base B ×1
* Half-U Top A ×1
* Half-U Top B ×1
* Half-U Grid A ×1
* Half-U Grid B ×1
* Side Grid ×2

#### Herrajes

* Tuerca M4 ×8
* Tornillo M4 × 20 mm ×8
* Tornillo M4 × 10 mm ×4

---

## 🔗 Módulos prediseñados

### 🖥️ Placa M-ATX

![Placa M-ATX](images/M-ATX-Board.png)
![Placa M-ATX IRL](images/IRL/matx-frontview.png)

**Requiere separadores de bronce**

#### Herrajes

* Tuerca M4 ×3
* Tornillo M4 × 20 mm ×3
* Tornillo M4 × 10 mm ×4
* Separador de bronce ×6

Este módulo tiene una altura de 5U (75 mm de alto) y admite placas madre de hasta 55 mm de altura.

### 💾 Bahías para discos

![Bahías de 2,5" IRL](images/IRL/2,5-3,5-bays.png)

#### Bahías para discos de 2,5"

![Bahía de 2,5"](images/2,5-Disk-Bays.png)

#### Herrajes

* Tornillo M4 × 10 mm ×4

#### Bahías para discos de 3,5"

![Bahía de 3,5"](images/3,5-Disk-Bays.png)

#### Herrajes

* Tornillo M4 × 10 mm ×4

### ⚡ Placa para fuente de alimentación M-ATX

![Fuente de alimentación M-ATX](images/M-ATX-Power-Supply.png)
![Fuente de alimentación M-ATX IRL](images/IRL/atx-powersupply-front.png)

Esta placa puede alojar una fuente de alimentación ATX completa.

#### Herrajes

* Tornillo para fuente de alimentación ATX 6-32 ×4

### 🛜 Relé WiFi

![Relé WiFi](images/Wifi-Rele.png)
![Relé WiFi IRL](images/IRL/wifi-rele.png)

Este módulo puede alojar un [relé WIFI](https://www.amazon.com/-/es/MOES-Inteligente-Interruptor-Temporizador-Aplicación/dp/B0CPLNMXBJ?th=1) económico y un [conector de interbloqueo](https://www.mercadolibre.com)

---

## 🏗️ Ejemplos de montaje

### Ejemplo de montaje - Rack de servidor / Home Lab

![Ejemplo de montaje 1.1](images/IRL/example-overview.png)
![Ejemplo de montaje 1.2](images/IRL/example-back-overview.png)

Este montaje muestra una configuración completa de servidor que incluye:

* **Unidad Completa** con placa madre M-ATX (parte inferior)
* **Bahías para discos** con unidades SATA de 2,5 y 3,5" para almacenamiento
* **Media Unidad** para la gestión de la alimentación

---

## 📁 Archivos

* Fusion 360 (F3D): [3D-Models/Parametric/Open-Rack.f3d](https://github.com/ElPelucaBeheran/Open-Rack/blob/main/3D-Models/Parametric/Open-Rack.f3d)
* STEP: [3D-Models/Parametric/Open-Rack.step](https://github.com/ElPelucaBeheran/Open-Rack/blob/main/3D-Models/Parametric/Open-Rack.step)
* Carpeta principal de archivos STL (Lista para imprimir): [3D-Models/STLs](https://github.com/ElPelucaBeheran/Open-Rack/tree/main/3D-Models/STLs)

---

## 👥 Créditos

Este proyecto fue posible gracias a las contribuciones de:

* [**sincodda**](https://github.com/sincodda)
* [**Tomás López Tur**](https://github.com/TomasLopezTur)
* [**FabLab VLA**](https://github.com/FabLabVLA)

Un agradecimiento especial a todos los colaboradores que han ayudado a desarrollar y mejorar el sistema Open-Rack.
