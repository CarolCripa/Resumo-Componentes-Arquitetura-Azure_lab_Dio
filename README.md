# Resumo-Componentes-Arquitetura-Azure_lab_Dio
Um resumo "Hands-on" com prints e observações sobre alguns pontos da Arquiturura e Componentes da Microsoft Azure:

1. Regiões (Zonas de Disponibilidade)
> - O Azure oferece 60 regiões (+ de 140 países);
> - As regiões são compostas de 1 ou + datacenters muito próximos;
> - Fornecem flexibilidade e escala p/ reduzir  a latência do cliente;
> - As regiões preservam a residência dos dados c/ uma oferta abrangente de conformidade (LGPD);
> - As Zonas de Disponibilidade, fornecem proteção contra tempo de inatividade devido a falha do datacenter;
> - Sepera os datacenters dentro da mesma região;
> - Cada datacenter é equipado c/ alimentação, resfriamento e rede independentes;
> - Conectadas por meio de redes privadas de fibra óptica.

2. Pares de Regiões
> - No mínino 300 milhas de separação entre pares de regiões;
> - Replicação automática p/ alguns serviços;
> - Recuperação de região priorizada em caso de interrupção;
> - As atualizações são distribuídas sequencialmente p/ minimizar o tempo de inatividade.

3. Regiões Soberanas do Azure

**Serviços Governamentais dos EUA**:
> - Atende às necessidades de segurança e conformidade das agências federais, governos estuais e locais dos EUA e seus provedores de soluções.

**Azure Govertamental**:
> - Instância separada do Azure;
> - Fisicamente isolada de implantações que não sejam do governo dos EUA;
> - Acessível somente as pessoas verificadas e autorizadas.

**Recursos do Azure na China**:
> - Instãncia fisicamente separada dos serviços de nuvem do Azure operados pela 21Vianet;
> - Todos os dados permanecem dentro da China p/ garantir a conformidade.

4. Grupos de Recursos
> - Um grupo de recursos é um contêiner que usasse para gerenciar e agregar recursos em uma única unidade;
> - Os recursos podem existir em diferentes regiões;
> - Recursos podem ser movidos p/ diferentes grupos de recursos;
> - Os app's podem utilizar vários grupos de recursos.
> - *Ex's:*<br>
1- web + BV, VM, armazemamento;<br>
2- web e banco de dados;<br>
3- máquina virtual;<br>
4- armazemaneto.

5. Assinaturas do Azure
> - Uma conta pode ter diversas assinaturas mas uma assinatura está associada apenas à uma conta;
> - Cada assinatura do Azure fornece acesso autenticado e autorizado às contas do Azure;
> - Sobre limite de cobrança: gera relatórios de cobrança e faturas separadas para cada assinatura;
> - Sobre limite do controle de acesso: gerencia e controla o acesso aos recursos que os usuários podem provisionar c/ assinaturas específicas.

6. Grupos de Gerenciamento
> - Podem incluir várias assinaturas do Azure;
> - As assinaturas herdam as condições aplicadas ao grupo de gerenciamento;
> - Por uma lógica hierárquica temos os Grupos de Gerenciamento que administram as Assinaturas e os Grupos de Recursos que apoiam os Recursos.

<img src="/home/carol/imagens/Lab-Dio/1_Explorando-datacenters-globais-Microsoft.png">
![1_Explorando-datacenters-globais-Microsoft](https://github.com/user-attachments/assets/af618397-9c60-4b83-8407-03beb969222d)


