# Datos de Campañas de Campo / Field Campaign Data
---
Este repositorio es el centro de acopio para todos los datos de reflectividades (en formato CSV) y datos LiDAR obtenidos durante nuestras campañas de campo. 
Los datos provienen de las campañas de IVIA, COPSEMAR e IRTA realizadas en 2022, 2023 y 2024.
---

This repository serves as the central hub for all reflectance data (in CSV format) and LiDAR data collected during our field campaigns. 
The data originates from the IVIA, COPSEMAR, and IRTA campaigns conducted in 2022, 2023, and 2024.

---

## Estructura de Directorios / Directory Structure

Hemos organizado los datos de forma intuitiva para facilitar su localización y acceso. La estructura de directorios sigue un patrón lógico, permitiendo encontrar rápidamente la información deseada.

We've organized the data intuitively to facilitate its location and access. The directory structure follows a logical pattern, allowing you to quickly find the desired information.

### Explicación de la Estructura / Structure Explanation

* **[CAMPAÑA]**: Los directorios de primer nivel, como `IVIA`, `COPSEMAR`, e `IRTA`, identifican la **campaña de campo específica** de donde provienen los datos. Esto permite una clara segregación por origen.
    * **[CAMPAIGN]**: The top-level directories, such as `IVIA`, `COPSEMAR`, and `IRTA`, identify the **specific field campaign** from which the data originates. This allows for clear segregation by source.

* **[AÑO]**: Dentro de cada directorio de campaña, encontrarás subdirectorios con el formato `YYYY` (por ejemplo, `2022`, `2023`, `2024`). Estos indican el **año** en que se recolectaron los datos, facilitando la navegación cronológica.
    * **[YEAR]**: Within each campaign directory, you'll find subdirectories in `YYYY` format (e.g., `2022`, `2023`, `2024`). These indicate the **year** the data was collected, facilitating chronological navigation.

* **[TIPO_DE_DATO]**: Finalmente, dentro de cada directorio anual, hay dos subdirectorios principales que separan los datos por su **tipo**:
    * `reflectividades/`: Este directorio contiene todos los archivos de reflectividad, que están en formato **CSV**.
    * `lidar/`: Aquí se almacenan todos los datos **LiDAR**. Pueden incluir varios formatos de archivo (por ejemplo, `.las`, `.laz`, etc.).

    * **[DATA_TYPE]**: Finally, within each annual directory, there are two main subdirectories that separate the data by its **type**:
        * `reflectividades/`: This directory contains all reflectivity files, which are in **CSV** format.
        * `lidar/`: All **LiDAR** data is stored here. This may include various file formats (e.g., `.las`, `.laz`, etc.).

---
