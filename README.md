# Cloud Ready Backup – Despliegue automatizado (Meriti OEM)

Crea en <12 minutos:
- Proyecto nuevo GCP
- VM Debian + CubeBackup OEM 100 % configurado
- Bucket Coldline + IP pública estática
- Todo el rebranding Meriti + índice en /opt/crb/index

## Uso (para soporte junior)

```bash
cp terraform.tfvars.example terraform.tfvars
nano terraform.tfvars   # ← completar 9 líneas
terraform init
terraform apply -auto-approve