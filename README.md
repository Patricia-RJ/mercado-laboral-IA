# 🤖 Mercado-laboral-IA 

Análisis del mercado global de IA 2025 & planificación de carrera profesional

## 📖 Descripción
Este proyecto presenta un **análisis del mercado global de Inteligencia Artificial y planificación de carrera profesional**, basado en el dataset “Global AI Job Market & Salary Trends 2025” de Kaggle, que recopila 15 000 ofertas de empleo publicadas entre enero 2024 y abril 2025, con variables clave como salario, modalidad laboral, industria, experiencia, ubicación y habilidades principales.

El informe aborda los siguientes objetivos:
- **Monitorizar la dinámica de oferta** de empleo en IA.
- **Evaluar la estructura salarial**, incluyendo medianas y percentiles.
- **Comparar modalidades laborales** (presencial, híbrido, remoto).
- **Mapear brechas** salariales por nivel de experiencia y región.
- **Detectar las skills más demandadas** y tendencias emergentes en el sector.

## 🗂 Estructura del proyecto

```plaintext
├── ai_job_dataset.xlsx  
│   └─ Dataset original de ofertas y demandas de empleo en IA  
├── Informe Análisis Mercado laboral de IA 2025.pdf  
│   └─ Informe detallado del análisis del mercado global de IA (enero 2024–abril 2025)  
├── Mercado Laboral Global de IA 2025.xlsx  
│   ├─ Hoja “IA_job_dataset”  
│   │   └─ Tabla con los datos ya limpios y preparados  
│   ├─ Hoja “Análisis”  
│   │   └─ Realización de KPIs, tablas dinámicas, gráficos dinámicos y segmentadores  
│   └─ Hoja “Dashboard”  
│       └─ Vista interactiva del proyecto  
└── README.md  
    └─ Descripción del proyecto, guía de uso y estructura de carpetas

## 🛠 Instalación y Requisitos

Para consultar y trabajar con estos archivos necesitas:
- Microsoft Excel (o LibreOffice Calc) para abrir los .xlsx.
- Visor de PDF para el informe.
- Opcional (análisis con Python):

python3 -m venv venv
source venv/bin/activate
pip install pandas openpyxl

## 📊 Resultados y conclusiones

### Resultados 
- Salario mediano global: 99 705 USD.
- Percentiles:
  -- 25 %: 70 180 USD
  -- 75 %: 146 409 USD
- Brecha absoluta entre niveles: Entry y Executive: 124 299 USD.
- Salario medio por nivel:
  -- Junior (Entry): 63 133 USD;
  --  Mid: 93 365 USD;
  --  Senior: 130 357 USD;
  --  Executive: 187 432 USD
- Variación geográfica:
  -- Países con salarios más altos: Suiza (170 639 USD), Dinamarca (165 652 USD), Noruega (159 491 USD), EE. UU. (146 833 USD).
  -- Países con salarios más bajos: India (84 236 USD), China (84 899 USD), Austria (85 175 USD).
- Modalidad laboral:
  -- Presencial: 33,8 %
  -- Híbrido: 33,4 %
  -- Remoto: 32,8 %
- Demanda por experiencia:
  -- 0–4 años: 7 499 ofertas (50 %)
  -- 5–9 años: 3 741 ofertas
- Skills más demandadas:
  -- Python (1.491 ofertas)
  -- SQL (962)
  -- Kubernetes (863)
- Evolución temporal:
  -- Pico máximo en abril 2024 (985 ofertas)
  -- Mínimo en febrero 2025 (840 ofertas)
- Rol destacado: Machine Learning Researcher con 808 ofertas.

### Conclusiones:

- Gran dipersión salarial con una brecha media de 124.299 USD entre junior y ejecutivos.
- Amayor nivel profesional, mayor salario: los ejecutivos ganan un 62% más que la media.
- Los contratos full-time y el sector de consultoría ofrecen salarios ligeramente superiores.
- Suiza, Dinamarca y Noruega ofrecen los sueldos más altos. Países como India o China presentan salarios mucho más bajos.
- las ofertas se reparten casi por igual entre trabajo presencial, híbrido y remoto.
- Alta demanda de perfiles junior.
- Python lidera las habilidades más buscadas, seguido de SQL, Kubernetes y Scala.
- Tendencia estable en el mercado laboral.
- Machine Learning Researcher destaca como rol clave.

##  🔄 Próximos Pasos:

Ideas para futuros análisis o expasión del proyecto:
- ➕ Ampliar el dataset con otras fuentes (p. ej. portales de empleo).
- 🛠 Desarrollar scripts en Python/R para limpiar y visualizar datos de manera automatizada.
- 🤖 Implementar un modelo predictivo de oferta/demanda laboral.

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, por favor:

1. Abre una **issue** para discutir la idea o reportar un problema.  
2. Haz un **fork** de este repositorio y crea una nueva rama:

   git checkout -b mi-mejora.

3.Realiza tus cambios y haz commit con un mensaje claro:

git commit -m "Descripción de mi mejora"

4.Sube tu rama al repositorio remoto:

 git push origin mi-mejora

5.Abre un Pull Request desde tu rama hacia main.
Gracias por tu interés y tu ayuda 🙌.

## Patricia Romo Jiménez - Máster en Data Analytics en Hack(io) by The Power
