# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS  

**Data:** 24/08/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Pedro D. Melo  

---

## Introdução  
Este relatório apresenta o processo de implementação de ferramentas em nuvem na empresa **Abstergo Industries**, realizado pelo responsável **Pedro D. Melo**.  
O objetivo do projeto foi:  
- *Elencar 3 serviços AWS com finalidade prática*  
- *Realizar diminuição de custos imediatos*  
- *Garantir escalabilidade e monitoramento em tempo real*  

---

## Descrição do Projeto  
O projeto de implementação de ferramentas foi dividido em **3 etapas**, cada uma com seus objetivos específicos.  
A seguir, serão descritas as etapas do projeto:  

---

### Etapa 1  
- **Nome da ferramenta:** Amazon S3  
- **Foco da ferramenta:** Armazenamento seguro e escalável de arquivos  
- **Descrição de caso de uso:** Funcionários salvam relatórios internos → arquivos são automaticamente enviados para buckets no **S3**, eliminando a dependência de servidores locais e garantindo backups automáticos.  

---

### Etapa 2  
- **Nome da ferramenta:** Amazon RDS (MySQL)  
- **Foco da ferramenta:** Banco de dados relacional gerenciado, com backup e alta disponibilidade  
- **Descrição de caso de uso:** O sistema da empresa acessa registros diretamente no **RDS**, permitindo consultas rápidas e seguras. Se houver falha em um servidor, o RDS realiza failover automático.  

---

### Etapa 3  
- **Nome da ferramenta:** Amazon CloudWatch  
- **Foco da ferramenta:** Monitoramento de métricas e geração de alertas em tempo real  
- **Descrição de caso de uso:** Caso o **RDS** apresente indisponibilidade ou o uso de armazenamento no **S3** atinja limites, o **CloudWatch** envia alertas por e-mail para a equipe de TI, permitindo ação imediata.  

---

## Conclusão  
Com a implementação dos serviços AWS, a Abstergo Industries conseguiu:  
- Reduzir custos de infraestrutura física  
- Melhorar a segurança e disponibilidade dos dados  
- Monitorar seus sistemas de forma proativa e eficiente  
