# Resumo-Componentes-Arquitetura-Azure_lab_Dio
Um resumo "Hands-on" com prints e observações sobre alguns pontos da Arquiturura e Componentes da Microsoft Azure:

1. Regiões (Zonas de Disponibilidade)
> - O Azure oferece 60 regiões (+ de 140 países);
> - As regiões são compostas de 1 ou + datacenters muito próximos;
> - Fornecem flexibilidade e escala p/ reduzir  a latência do cliente;
> - As regiões preservam a residência dos dados c/ uma oferta abrangente de conformidade (LGPD);
> - As Zonas de Disponibilidade, fornecem proteção contra tempo de inatividade caso houver a falha do datacenter;
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
> - Instância fisicamente separada dos serviços de nuvem do Azure operados pela 21Vianet;
> - Todos os dados permanecem dentro da China p/ garantir a conformidade.

4. Grupos de Recursos
> - Um grupo de recursos é um contêiner que serve para gerenciar e agregar recursos em uma única unidade;
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

Abaixo seguem os prints do "Hands-on" feito no lab:

![1_Explorando-datacenters-globais-Microsoft](https://github.com/user-attachments/assets/af618397-9c60-4b83-8407-03beb969222d)
Legenda-1: Explorando os DataCenters globais da Microsoft.
<br>
<br>

![2_Info's-região-disponibilidade-Brasil](https://github.com/user-attachments/assets/d0064ca5-916e-41aa-86eb-5e9effe45a35)
Legenda-2: Informações sobre regiões de disponibilidade - Barsil.
<br>
<br>

![3_Tour-centro-dados-Microsoft](https://github.com/user-attachments/assets/d6301d49-eb71-4cce-ab91-b682bb7523a7)
Legenda-3: Tour no Centro de Dados da Microsoft.
<br>
<br>

![4_Explorando-mapa-infra](https://github.com/user-attachments/assets/398ec295-0b59-4064-bcd4-35f35fe4c4a6)
Legenda-4: Explorando o Mapa de Infraestrutura.
<br>
<br>

![5_Sala-operações](https://github.com/user-attachments/assets/0ee28268-1c3e-492c-9f5d-478737ccf6ae)
Legenda-5: Sala de Operações.
<br>
<br>

![6_Sala-servidores](https://github.com/user-attachments/assets/b4ce264c-0f69-402e-9085-f24a8e6ce386)
Legenda-6: Sala dos Servidores.
<br>
<br>

![7_Área-mecânica](https://github.com/user-attachments/assets/11c7b52d-4754-406e-94ed-1fad3ec46756)
Legenda-7: Área mecânica.
<br>
<br>

![8_Sala-rede](https://github.com/user-attachments/assets/858aae60-2284-45cf-80fa-8d8337f26edd)
Legenda-8: Sala de Redes.
<br>
<br>

![9_Portal-azure](https://github.com/user-attachments/assets/cf9881f1-8295-4936-9068-e0ec9789ddd3)
Legenda-9: Conhecendo o Portal da Azure.
<br>
<br>

![10_criando-grupo-recursos](https://github.com/user-attachments/assets/6e7e5488-3d7b-494e-a34c-fa9245a2f66a)
Legenda-10: Criando um Grupo de Recursos.
<br>
<br>

![11_Recurso-criado](https://github.com/user-attachments/assets/7aecf598-f147-45b3-9da1-8eef8568eaab)
Legenda-11: Recurso Criado.
<br>
<br>

![12_Criando-rede-virtual](https://github.com/user-attachments/assets/349e5bd6-95cd-4eed-a525-5aeb8a70fc84)
Legenda-12: Criando uma Rede Virtual.
<br>
<br>

![13_Dados-localização-recurso](https://github.com/user-attachments/assets/56450739-cc76-4699-a648-2a8d7800a9e2)
Legenda-13: Dados e Localização do recurso.
<br>
<br>

![14_Log-atividade-finalizado](https://github.com/user-attachments/assets/92c848c6-6b25-4559-a807-d4b057073570)
Legenda-14: Log de Atividade realizado e finalizado.













