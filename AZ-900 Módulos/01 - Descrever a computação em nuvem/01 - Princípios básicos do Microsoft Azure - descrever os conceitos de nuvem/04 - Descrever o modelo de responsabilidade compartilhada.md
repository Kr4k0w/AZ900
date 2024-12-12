# Modelo de Responsabilidade Compartilhada

## Definição  
No modelo de responsabilidade compartilhada, as tarefas de gerenciamento e segurança são divididas entre o provedor de nuvem e o consumidor.

## Responsabilidades

### Consumidor  
- **Dados e informações armazenados na nuvem.**  
- **Dispositivos autorizados a acessar a nuvem.**  
- **Contas e identidades de usuários, serviços e dispositivos.**

### Provedor de Nuvem  
- **Segurança física do datacenter.**  
- **Energia, resfriamento e conectividade de rede.**  
- **Manutenção de hosts e infraestrutura física.**

### Divisão conforme o tipo de serviço:
1. **IaaS (Infraestrutura como Serviço):** Consumidor gerencia mais, incluindo sistemas operacionais e aplicativos.  
2. **PaaS (Plataforma como Serviço):** Responsabilidades compartilhadas entre o consumidor e o provedor, como manutenção de aplicativos e infraestrutura subjacente.  
3. **SaaS (Software como Serviço):** Provedor assume a maioria das responsabilidades, exceto dados e identidades.
   
![Diagram showing the responsibilities of the shared responsibility model.](https://learn.microsoft.com/pt-br/training/wwl-azure/describe-cloud-compute/media/shared-responsibility-b3829bfe.svg)

## Benefício  
Esse modelo permite que o consumidor foque em gerenciar suas aplicações e dados, enquanto o provedor cuida da infraestrutura e segurança física.
