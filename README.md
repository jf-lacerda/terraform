Fixando conteúdos:

Primeiro passo inserir as credenciais

export AWS_ACCESS_KEY_ID=MY_ACCESS_KEY_ID
export AWS_SECRET_ACCESS_KEY=MY_SECRET_ACCESS_KEY

Comando para criar bucket no S3 com terraform;

Iniciar o terraform: terraform init

Ver o que será criado(alterado): terraform plan

*Criar um plano em um arquivo: terraform plan -out plan.out

Na hora de fazer o apply menciona o plano que você quer usar: terraform apply plan.out

Criar o bucket: teraform apply

Apagar o bucket: terraform destroy