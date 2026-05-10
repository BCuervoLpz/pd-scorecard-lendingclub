## Día 1 — [11-5-2026]

### Objetivos del plan
1.Definición de default y construcción del target binario (porque conecta directo con UTP/fallidos/curas del JD)
2.Modelización PD con regresión logística, WOE binning y scorecard (es el corazón del proyecto)
3.Backtesting con Gini, KS y PSI, e interpretación regulatoria del PSI (engancha con "respuesta a requerimientos supervisores")
4.IFRS 9: staging y diferencia PD a 12 meses vs lifetime (la conexión con el marco normativo)
5.Power BI para cuadros de mando de riesgo conectados al output del modelo

### Aprendido hoy
- Diferencia entre Anaconda Prompt, Git Bash y PowerShell, y cuándo usar cada una.
- Flujo completo de Git: configurar identidad, generar clave SSH, conectar a GitHub, clonar, commit y push.
- Estructura estándar de un proyecto data science (data/raw vs processed, separación notebooks/src, .gitignore disciplinado).
- Por qué se usan entornos conda separados y por qué pip dentro de conda es la práctica actual.

### Bloqueos
- Confusión inicial entre VS Code y VS Code Insiders en el instalador de Git.
- Las preguntas seguidas de ssh-keygen aparecían una a una y no las identifiqué al principio.
- El error de identidad de Git al primer commit (user.name/email no estaban grabados como esperaba).

### Para mañana
- Descargar el dataset Lending Club desde Kaggle.
- Empezar DataCamp: Data Manipulation with pandas (capítulos 1-2).
- Primer notebook 01_eda.ipynb cargando el CSV y explorando shape, dtypes, distribución de loan_status.