🚀 AWS CloudFormation Labs: VPC Infrastructure
Este repositório contém meus estudos e implementações de Infraestrutura como Código (IaC) utilizando o AWS CloudFormation. O objetivo é documentar a criação de ambientes escaláveis e seguros na Amazon Web Services.

📋 Sobre o Projeto
O template principal deste laboratório provisiona uma arquitetura de rede padrão (VPC) seguindo as melhores práticas de segmentação e segurança. Esta estrutura serve como base para hospedar aplicações que exigem tanto acesso público quanto isolamento de dados.

Recursos provisionados:
VPC: Rede virtual privada com endereçamento CIDR 10.0.0.0/16.

Subnet Pública: Configurada para permitir acesso à Internet e mapeamento automático de IP público.

Subnet Privada: Isolada da rede externa, ideal para bancos de dados e instâncias críticas.

Internet Gateway (IGW): Porta de saída para tráfego na sub-rede pública.

Route Tables: Configuração de rotas automatizada para direcionar o tráfego de saída.

DNS Support: Habilitação de resolução de nomes internos para as instâncias.

🛠️ Tecnologias Utilizadas
AWS CloudFormation: Motor de IaC para automação de recursos.

JSON: Formato de estruturação do template.

AWS CLI: Interface de linha de comando para validação e deploy.