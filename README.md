# tfm-app-deployment (Autoservicio 4)

Fusiona la configuración en `<entorno>-<app>-app`, lanza el pipeline CI/CD (tests, build, Trivy, push a ECR, despliegue en ECS), localiza la IP pública y comprueba `/health`.

Entrada (`json_data`): `environment_name`, `app_name`, `app_version` (opcional).
