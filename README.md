Integração Amazon SES e S3 para Armazenamento de E-mails
Este projeto configura uma solução automatizada para receber e-mails através do Amazon Simple Email Service (SES) e armazená-los diretamente em um bucket do Amazon S3. Essa integração facilita o arquivamento e o processamento posterior dos e-mails recebidos.

📝 Descrição do Projeto
A solução utiliza o Amazon SES para receber e-mails destinados a um domínio específico e os armazena automaticamente em um bucket do Amazon S3. Isso permite que os e-mails sejam acessados e processados conforme necessário, aproveitando a escalabilidade e a segurança dos serviços AWS.

💡 Funcionalidades
Recebimento de E-mails: Configuração do Amazon SES para receber e-mails enviados para um domínio verificado.
Armazenamento no S3: Entrega automática dos e-mails recebidos em um bucket do Amazon S3 designado.
Organização dos E-mails: Possibilidade de organizar os e-mails no S3 por data, remetente ou outros critérios definidos.
Notificações (Opcional): Integração com o Amazon SNS para notificar sobre a chegada de novos e-mails.

🛠️ Tecnologias Utilizadas
Amazon SES: Serviço de e-mail escalável para recebimento e envio de e-mails.
Amazon S3: Serviço de armazenamento de objetos seguro e escalável.
AWS CloudFormation: Para provisionamento de recursos através de templates YAML.
