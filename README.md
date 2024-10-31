# repo-lab-dio-az900
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO


## Resumo - 1º Lab | Benefícios da Nuvem Azure

Até o momento aprendemos a configurar idioma/região, aparências/temas, onde ficam as categorias dos serviços da azure, e o mais importante, que se um serviço estiver em "versão prévia" ele pode sumir a qualquer momento, e nós não podemos reclamar para a Microsoft, pois é algo que está em teste/avaliação e não tem garantia que vai continuar funcionando.


## Resumo - 2º Lab | Benefícios da Nuvem Azure

Nessas últimas aulas pude aprender bastante coisa que considero importante, como:

- CapEx e OpEx: onde entendi que o **CapEx** seria o modelo de negócio que investimos de imediato em aquisição de bens como prédios, máquinas.. e ao longo do seu tempo esse modelo vai se pagando, porém mantendo custos fixos como energia, manutenção, segurança, entre outros. Já no modelo **OpEx** nós basicamente alugamos essas máquinas e prestações de serviços, onde pagamos somente pelo que usamos, isso quer dizer que se não usarmos o serviço por 15 dias (ou ele ficar fora do ar), só pagaremos pelos outros 15 dias do mês que utilizamos.

- Escalabilidade Horizontal e Vertical: onde a escalabilidade vertical seria o aumento de perfomance da máquina e a escalabilidade horizontal seria o aumento da quantidade de máquinas disponíveis.

- Elasticidade: a elasticidade é o que define o quanto o seu ambiente vai escalar tanto horizontalmente, como verticalmente, tudo isso definido por parâmetros de perfomance, ou seja, você pode configurar para a Azure iniciar outra máquina assim que atingir 70% de uso da máquina atual, garantindo eficiência e economia.

- Confiabilidade: como a palavra já diz em si, seria a confiança que você terá o serviço disponível e que ele pode se recuperar de falhas, mas não vamos entender mal, para isso temos que configurar o serviço para que ele atue em mais de uma região, sendo assim, mesmo que ocorra algum problema ou evento catastrófico em uma das regiões, a outra continuará funcionando.

- Previsibilidade: seria outra confiança na núvem, a confiança que ela vai garantir o desempenho e o custos que foram ofertados.

- Segurança: aprendi que não é só parte da núvem garantir a segurança do ambiente, mas é uma via de mão dupla, ela te dá as ferramentas necessárias para garantir a segurança, porém, você tem que saber o que está fazendo e configurando, para que, mesmo sem querer, não permita o acesso indevido de outros usuários. Outras implantações como PaaS ou Saas são estratégias melhores para quem quer que a aplicação de patches de segurança sejam implantadas automaticamente.
  
- Governança: Entendi que é a sinalização dos padrões da empresa que ajudam a garantir que estamos utilizando os recursos que estão em conformidade e que resolvem os problemas. Definindo isso o mais cedo possível, você ajuda a empresa a se manter dentro dos padrões, atualizada, segura e bem gerenciada.

- Gerenciabilidade: onde temos total controle, supervisão da infraestrutura, dos serviçoes e das aplicações que estão sendo executadas, podendo ser incluídas políticas, estratégias, tecnologias, segurança e eficiência para uma melhor performance e segurança dos recursos.


## Resumo - 3º Lab | Tipos De Serviço De Nuvem

Neste lab aprendi mais sobre os tipos de serviços da nuvem (SaaS, IaaS, Paas) e que cada um tem suas particularidades e responsabilidades, tanto do lado do provedor como do cliente, conforme vimos no termo da responsabilidade compartilhada:

![image](https://github.com/user-attachments/assets/28803454-d78e-42f2-b0fe-25d6196534cb)

Onde o modelo de SaaS seria o que mais te isenta de responsabilidades, sendo necessárias apenas pequenas configurações para funcionar; o PaaS seria o meio termo, onde o cliente é isento de responsabilidades como datacenter (físico), rede (física), host (físico) e sistema operacional, porém, compartilha a responsabilidade dividida nos diretórios, acessos, configurações de rede, e das aplicações; Já o Iaas seria onde mais "sofremos" e temos quase que toda a responsabilidade no nosso colo, sendo isento apenas do datacenter (físico), rede (física) e host (físico).

Ao final do lab vimos mais sobre as zonas de redundância, máquina virtual, como criar um banco de dados SQL e a precificação do mesmo.
