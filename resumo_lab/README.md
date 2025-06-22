# 🌐 Bootcamp DIO - Microsoft 50 Anos: Computação em Nuvem com Azure

O <b>Bootcamp DIO - Microsoft 50 Anos: Computação em Nuvem com Azure</b> propõe apresentar uma base sólida sobre o funcionamento da plataforma Microsoft Azure, explicando como funciona a nuvem, como os serviços são organizados e como podemos começar a usar os recursos oferecidos pela plataforma. 

Este documento irá apresentar o resumo dos conteúdos apresentados até o momento, conforme solicitado pelo <b>Desafio de Projeto 01: 
Microsoft Azure - Localizando Serviços por Categoria</b>. 


## ☁️ Computação em Nuvem

A computação em nuvem consiste na oferta de recursos computacionais através da Internet, permitindo que empresas e usuários acessem serviços de infraestrutura, plataforma e software sem a necessidade de manter servidores ou datacenters locais. Entre as vantagens desse modelo estão a escalabilidade sob demanda, alta disponibilidade, elasticidade, segurança, previsibilidade de custos e facilidade de gerenciamento.

### Modelos de Nuvem

Existem três principais modelos de implantação em nuvem: 
- <b>Nuvem pública:</b> os recursos são disponibilizados por um provedor (como a própria Azure) e acessados via Internet; 
-  <b>Nuvem privada:</b> geralmente mantida internamente por uma organização com controle total sobre a infraestrutura; 
-  <b>Nuvem híbrida:</b> combina as duas abordagens, oferecendo flexibilidade para atender a diferentes demandas e requisitos regulatórios.

### Modelos de Serviços

Existem três modelos de serviço, sendo: 
- <b>IaaS (Infraestrutura como Serviço):</b> este modelo oferece recursos como máquinas virtuais, redes e armazenamento sob demanda; 

- <b>PaaS (Plataforma como Serviço):</b> fornece ambientes gerenciados para desenvolvimento e implantação de aplicações;

- <b>SaaS (Software como Serviço):</b> neste modelo o usuário utiliza diretamente aplicações hospedadas na nuvem, como o Microsoft 365.


### CapEx e OpEx

Um ponto que diferencia bastante o uso da nuvem é a forma de investimento. Enquanto o modelo on premise possui um alto investimento em CapEx, o modelo em nuvem possui investimento de OpEx. 

- <b>CapEx:</b> pode ser descrito como despesa de capital, envolve os investimentos para comprar os servidores e para montar a infraestrutura. São caracterizados como pagamentos não recorrentes. É um grande ofensor de custos no modelo on premise.
- <b>OpEx:</b> pode ser descrito como despesa operacional. São pagamentos recorrentes durante toda a operação de determinado projeto. É o modelo que abrange o investimento da computação em nuvem, que pode se basear em pagar conforme o uso, reduz o custo inicial e dá mais flexibilidade para o negócio.

### Arquitetura da Azure

A estrutura da Azure é dividida em regiões, que são conjuntos de datacenters espalhados pelo mundo. Algumas dessas regiões possuem zonas de disponibilidade, que funcionam como backups físicos entre datacenters da mesma região. Também existem pares de regiões, usados para garantir alta disponibilidade em casos de falha.

A Azure também possui regiões especiais que seguem regras específicas de conformidade, como, por exemplo, a versão governamental dos EUA e a versão para a China.

### Organização de Recursos

Na Azure, os recursos (como VMs, bancos, redes) ficam organizados dentro de grupos de recursos, que ajudam a gerenciar tudo de forma mais eficiente. O acesso aos serviços é feito por meio de assinaturas, que controlam cobrança e permissões. É possível agrupar as assinaturas em grupos de gerenciamento, para facilitar os processos em maior escala.

### Serviços de Computação

A Azure oferece diversos serviços de computação, dentre os principais podemos citar:
 - <b>Máquinas virtuais:</b> permitem controle total sobre os recursos e podem ser personalizadas conforme a demanda do usuário;
 - <b>Contêineres:</b> permitem a execução de aplicações, dispensando o usuário de se preocupar com a máquina em si; 
 - <b>Azure Functions: </b>permitem a execução do código sob demanda sem gerenciar infraestrutura;
 - <b>App Service</b> fornece uma plataforma gerenciada para aplicações web e APIs com suporte a várias linguagens de programação.

### Recursos de Rede

Na parte de rede, a Azure oferece a VNet (Virtual Network), que permite a comunicação entre recursos e com redes externas de forma segura e escalável. O DNS da Azure complementa essa estrutura, oferecendo gerenciamento de nomes de domínio com alta performance, segurança e integração com outros serviços Azure.

### Soluções de Armazenamento

A Azure oferece diferentes soluções de armazenamento, como Blob, Fila, Tabela e Arquivos, os quais possuem camadas de acesso específicas (Hot, Cool e Archive) dependendo da frequência de uso. 

Também é possível escolher entre diversos níveis de redundância, garantindo a disponibilidade dos dados conforme a necessidade. 

Para a movimentação e migração de grandes volumes de dados, a Azure oferece ferramentas como AzCopy, Gerenciador de Armazenamento da Azure e Azure Data Box, especialmente útil em ambientes com conectividade limitada.

## 💻 Práticas

Além do acompanhamento dos professores durante a apresentação detalhada dos recursos da Microsoft Azure, foi ensinado o passo a passo para criar uma conta, com destaque para as opções gratuitas disponíveis, que podem ser pelo período de teste de 30 dias ou por meio do cadastro como estudante, que disponibiliza o acesso gratuito por 1 ano.




