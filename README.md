# Mini-Osciloscopio

## 📚 Descripción
Implementación del **Mini Osciloscopio Xprotolab Plain** diseñado por [Gabotronics](https://www.gabotronics.com/categories/products/xprotolab-plain.html).  

Este proyecto fue realizado como parte del curso *Taller de Equipos Electrónicos (EC3083)* en la *Universidad Simón Bolívar*, utilizando un kit donado por **Gabotronics**. 

El proyecto consistió en: 
- ✅ Ensamblaje del circuito (soldadura de componentes SMD/THT).  
- ✅ Pruebas de funcionamiento.  
- ✅ Experimentación con diferentes señales.
- ✅ Visualización de las señales en PC mediante software dedicado.

## 🛠️ Tecnologías
- **Hardware**: PCB y componentes proporcionados por Gabotronics. 
    - [BOM](https://www.gabotronics.com/download/xproto-plain/xprotolab-plain-bom.xlsx). 
- **Software**: 
    - [XScopes PC Interface](https://www.gabotronics.com/product-info/xprotolab-pc-interface.html).
    - Driver WinUSB [ZADIG tool](https://www.gabotronics.com/download/xscopes/zadig_v2.0.1.162.exe).

## 📸 Media

### ⚡ PCB
![alt text](./Imagenes/PCB_front.jpeg)

![alt text](./Imagenes/PCB_back.jpeg)

### 📐 Esquemático/Footprints
![alt text](./Imagenes/esquematico.PNG)

![alt text](./Imagenes/xprotolab-plain-assembly.png)

### 📊 Pruebas
- #### Onda cuadrada con 555 astable
🎬 [Video](https://youtu.be/qR45TX839PM)

![alt text](./Imagenes/Test_555.jpeg)

![alt text](./Imagenes/555_astable_signal.PNG)

- #### Arbitrary Waveform Generator (AWG)
    - #### Onda senoidal
    ![alt text](./Imagenes/AWG_sine.PNG)
    - #### Onda triangular
    ![alt text](./Imagenes/AWG_triangular.PNG)
    - #### Onda cuadrada
    ![alt text](./Imagenes/AWG_Pulsos.PNG)
    - #### Onda RC
    ![alt text](./Imagenes/AWG_RC.PNG)
    - #### Onda ECG
    ![alt text](./Imagenes/AWG_ECG.PNG)

## ⚠️ Disclaimer  
- **Diseño original**: Propiedad de [Gabotronics](https://www.gabotronics.com/). Este repositorio 
documenta la implementación de su kit donado. 
- **Propósito**: Fines educativos y de portafolio personal. **No comercial**.   
- **Documentación técnica oficial**: Disponible en la [página de Gabotronics](https://www.gabotronics.com/categories/products/xprotolab-plain.html).
- **Licencia**: El diseño, firmware y el software para la visualización son propiedad intelectual de Gabotronics. 