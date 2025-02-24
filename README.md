**OSV-Scanner** es una herramienta de código abierto desarrollada por Google que permite identificar vulnerabilidades conocidas en las dependencias de un proyecto. Utiliza información de la base de datos OSV (Open Source Vulnerabilities) para escanear proyectos y detectar problemas de seguridad relacionados con las bibliotecas y componentes de código abierto utilizados en un repositorio. El propósito de OSV-Scanner es facilitar la gestión de seguridad en proyectos de software al proporcionar informes detallados sobre las vulnerabilidades presentes en las dependencias de un proyecto.

| **Technology** | **Compatible Lockfile(s)**                                        |
|----------------|--------------------------------------------------------------------|
| JavaScript     | package-lock.json, pnpm-lock.yaml, yarn.lock                       |
| Python         | Pipfile.lock, poetry.lock, requirements.txt*, pdm.lock, uv.lock    |
| PHP            | composer.lock                                                     |
| .NET Core      | deps.json                                                         |
| Java           | buildscript-gradle.lockfile, gradle.lockfile, gradle/verification-metadata.xml, pom.xml* |
