Título:

Integración Continua con GitHub Actions y Surge.sh

1. Objetivo

Implementar un pipeline de integración continua que despliegue automáticamente una página HTML en Surge.sh al realizar un push al repositorio en GitHub.

2. Herramientas utilizadas

Git

GitHub

GitHub Actions

Node.js

Surge.sh

3. Flujo de funcionamiento

Se crea repositorio local con index.html.

Se conecta con GitHub.

Se configura workflow en .github/workflows/main.yaml.

Se configuran secrets (SURGE_TOKEN y SURGE_DOMAIN).

Al hacer git push, se ejecuta automáticamente el deploy.

4. Evidencias:
   
<img width="885" height="401" alt="image" src="https://github.com/user-attachments/assets/0df4820e-0aec-448e-ae43-df64c5bc1397" />

<img width="886" height="439" alt="image" src="https://github.com/user-attachments/assets/538cae5e-2984-40a1-8511-92a004243277" />

<img width="883" height="383" alt="image" src="https://github.com/user-attachments/assets/9f3e7ddd-2b19-48e7-9291-91c9c2a1d63b" />


