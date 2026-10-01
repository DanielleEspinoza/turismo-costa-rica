# Turismo en Costa Rica: llegadas internacionales 2017-2025

Este proyecto analiza las llegadas internacionales de turistas a Costa Rica entre 2017 y 2025, con datos oficiales del Instituto Costarricense de Turismo (ICT). El objetivo es entender cómo ha evolucionado el turismo en el país, cuánto lo afectó la pandemia y de dónde provienen sus visitantes.

## Preguntas de análisis

1. **Evolución:** ¿cómo han cambiado las llegadas internacionales entre 2017 y 2025? ¿Cuánto cayeron durante la pandemia y en qué año se recuperó el nivel de 2019?
2. **Estacionalidad:** ¿qué meses concentran más llegadas de turistas? ¿El patrón de temporada alta y baja es igual para todos los mercados de origen? *(fase 2: requiere datos mensuales)*
3. **Mercados de origen:** ¿qué países y regiones aportan más turistas? ¿Todos los mercados se recuperaron de la misma forma después de la pandemia?
4. **Puertas de entrada:** ¿qué proporción de turistas llega por vía aérea frente a la vía terrestre y marítima? ¿Varía según la región de origen? *(el detalle por aeropuerto queda para la fase 2)*

## Datos

- **Fuente:** Instituto Costarricense de Turismo (ICT), [Informes estadísticos](https://www.ict.go.cr/es/estadisticas/informes-estadisticos.html)
- **Periodo:** 2017-2025
- **Contenido:** llegadas internacionales por año, país y región de origen. El dataset limpio tiene cuatro variables: `region`, `pais`, `anio` y `llegadas`.

## Estructura del repositorio

```
turismo-costa-rica/
├── data/
│   ├── raw/                  # Datos originales del ICT
│   └── processed/            # Datos limpios
├── notebooks/
│   └── 01_limpieza.ipynb     # Limpieza y validación de datos
├── figures/                  # Gráficos del análisis
├── requirements.txt          # Librerías necesarias
└── README.md
```

## Cómo ejecutarlo

1. Clonar el repositorio:

```bash
git clone https://github.com/DanielleEspinoza/turismo-costa-rica.git
cd turismo-costa-rica
```

2. Crear y activar un entorno virtual:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Instalar las librerías:

```bash
pip install -r requirements.txt
```

4. Abrir los notebooks de la carpeta `notebooks/` en orden.

## Estado del proyecto

- [x] Limpieza y validación de datos
- [ ] Análisis exploratorio
- [ ] Fase 2: extracción de datos mensuales y por aeropuerto de los informes PDF del ICT
- [ ] Conclusiones

## Autora

**Danielle Espinoza**, estudiante de Ingeniería en Ciencia de Datos en LEAD University.

[LinkedIn](https://www.linkedin.com/in/danielle-espinoza-abarca-8a9a2b38b)