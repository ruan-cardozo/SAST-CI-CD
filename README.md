# SAST-CI-CD: Pesquisa e Desenvolvimento de Ferramentas de CI/CD e Controle de Versão

- Grupo: Ruan Cardozo, Guilherme Kopsch, Guilherme Machado
- Data de Início: 03/09/2024
- Data de Entrega: 23/09/2024

---

## 2. Pesquisa Inicial (03/09 a 10/09)

### Ferramentas Escolhidas:
- **Controle de Versão**: GitLab e GitHub
- **CI/CD**: Jenkins e CircleCI

### Referências Utilizadas:
- https://medium.com/xebia-engineering/an-introduction-to-circleci-aa9464a86673
- https://medium.com/@habbema/hands-on-jenkins-1c585f4d939a
- https://medium.com/@habbema/jenkins-2a559187c640
- https://www.gocache.com.br/dicas/para-que-serve-jenkins-e-o-que-ele-pode-fazer/
- https://clickup.com/pt-BR/blog/147534/gitlab-vs-github?utm_source=google-pmax&utm_medium=cpc&utm_campaign=gpm_cpc_latam_nnc_pro_trial_all-devices_tcpa_lp_x_all-departments_x_pmax-loc-pt-br&utm_content=&utm_creative=_____&gad_source=1&gclid=Cj0KCQjw3bm3BhDJARIsAKnHoVX-Kz4MI06bse1SJj-wsO3eT_OlQQcXkFbY58JxolVKeZ8kXpiASVEaAhg2EALw_wcB
- https://www.dio.me/articles/github-x-gitlab-principais-diferencas#:~:text=A%20principal%20diferen%C3%A7a%20%C3%A9%20que,voc%C3%AA%20mesmo%20precisar%C3%A1%20integr%C3%A1%2Dlas.
- https://www.dio.me/articles/construindo-com-confianca-escolhendo-entre-github-e-gitlab-para-o-controle-de-versao

### Critérios de Escolha:

1. **Popularidade e Adoção no Mercado**:
   - Escolhemos o **GitHub** por ser um dos repositórios remotos mais amplamente utilizados no mundo. Sua popularidade oferece confiança, suporte contínuo, e uma vasta base de desenvolvedores e projetos que servem como referência. Além disso, suas funcionalidades gratuitas cobrem grande parte das necessidades de um pipeline moderno de CI/CD, o que o torna uma escolha natural para o controle de versão.

2. **Exploração e Aprendizado de Novas Ferramentas**:
   - O **GitLab** foi escolhido pela oportunidade de conhecer e experimentar uma plataforma que o grupo ainda não utilizou. Embora seja similar ao GitHub em várias funcionalidades, queremos entender suas diferenças e explorar suas características únicas, como a integração de CI/CD nativa. Essa escolha visa ampliar o conhecimento do grupo e avaliar o GitLab como uma alternativa viável em projetos futuros.

3. **Aplicação em Projetos Acadêmicos**:
   - O **Jenkins** foi selecionado porque será utilizado em um projeto de outra matéria. O objetivo é usar essa disciplina para aprofundar o entendimento da arquitetura e da configuração do Jenkins, facilitando sua implementação no outro contexto acadêmico. A experiência prática nesta fase permitirá que o grupo desenvolva uma base sólida para utilizar a ferramenta com mais confiança em outros projetos.

4. **Avaliação de Viabilidade e Comparação de Modelos**:
   - A inclusão do **CircleCI** no projeto reflete o desejo de explorar diferentes abordagens de CI/CD e comparar sua viabilidade em relação ao Jenkins. O CircleCI oferece um modelo simplificado e mais integrado, especialmente para quem utiliza GitHub e GitLab. Queremos avaliar se ele é uma alternativa mais prática ou eficiente para automação de pipelines, tanto no curto quanto no longo prazo, em comparação com o Jenkins.

---

## 3. Comparação das Ferramentas (10/09 a 17/09)

### Descrição das Ferramentas:

- **GitLab**:  
  O **GitLab** é uma plataforma completa de DevOps que inclui ferramentas de controle de versão, CI/CD nativo e gerenciamento de projetos. Seus **CI Pipelines** permitem configurar automação contínua de testes, builds e deploys diretamente dentro do sistema, sem a necessidade de ferramentas externas. Isso faz do GitLab uma solução integrada que cobre desde o planejamento até a entrega e monitoramento de software, ideal para equipes que buscam um fluxo de trabalho centralizado.

- **GitHub**:  
  **GitHub** é a plataforma de hospedagem de código mais popular do mundo, baseada no sistema de controle de versão Git. Além de gerenciar repositórios de código, o GitHub oferece o **GitHub Actions**, uma funcionalidade integrada de CI/CD que permite a automação de fluxos de trabalho, como testes, builds e deploys, além disso possui suporte para pull requests, onde podem ter Code Review, tem uma área separada para gerir projetos e diversas formas de personalizar isso. Essas funcionalidades, combinada com sua grande comunidade e suporte a integrações, faz do GitHub uma escolha popular tanto para desenvolvedores individuais quanto para grandes organizações.

- **Jenkins**:  
  **Jenkins** é uma ferramenta open-source para automação de pipelines de CI/CD, permitindo a integração contínua e a entrega contínua de software. Com centenas de plugins, o Jenkins é altamente customizável e permite que as equipes de desenvolvimento configurem seus próprios fluxos de trabalho, desde a compilação até a implantação. Ele é amplamente utilizado por sua flexibilidade e suporte a diferentes ambientes de desenvolvimento e produção.

- **CircleCI**:  
  **CircleCI** é uma plataforma de CI/CD com foco em automação eficiente e integração direta com ferramentas de controle de versão, como GitHub e GitLab. Ela permite a configuração de pipelines automáticos para testes, builds e deploys de forma rápida e escalável. Conhecida pela simplicidade na configuração e operação em ambientes de nuvem, o CircleCI oferece uma solução prática para equipes que buscam uma ferramenta de CI/CD de fácil implementação e gerenciamento.

---

### Critérios para Comparação:

1. **Facilidade de Uso**:
   - **GitLab**:  
     O GitLab oferece uma interface limpa e um fluxo de trabalho bem documentado, especialmente para usuários que buscam uma solução integrada para controle de versão e CI/CD. No entanto, para quem não está acostumado, pode ser um pouco mais complexo inicialmente devido à vasta gama de funcionalidades nativas.
   
   - **GitHub**:  
     Amplamente conhecido por sua simplicidade e interface amigável, o GitHub é fácil de usar, especialmente para novos usuários e pequenas equipes. Sua integração com **GitHub Actions** facilita o setup de pipelines automáticos sem a necessidade de grandes configurações externas.

   - **Jenkins**:  
     O Jenkins, apesar de ser altamente configurável e flexível, exige um nível técnico mais elevado para configuração inicial, especialmente devido à necessidade de instalação e configuração de plugins. É uma ótima escolha para usuários mais experientes que desejam controle total sobre o pipeline.

   - **CircleCI**:  
     Focado em simplicidade, o CircleCI é intuitivo e rápido de configurar, principalmente para quem utiliza plataformas populares como GitHub ou GitLab. A interface é clara e as opções pré-configuradas tornam a criação de pipelines bastante acessível para novos usuários.

---

2. **Integração com Outras Ferramentas**:
   - **GitLab**:  
     O GitLab é uma solução “tudo-em-um”, oferecendo integração nativa com ferramentas de CI/CD, além de ser altamente compatível com ferramentas de segurança, análise estática (SAST), e monitoramento. Ele também se integra facilmente a soluções de terceiros como Docker, Kubernetes e ferramentas de deploy contínuo.

   - **GitHub**:  
     A integração com **GitHub Actions** é o ponto forte, permitindo criar pipelines CI/CD diretamente na plataforma. GitHub também oferece integrações com diversas ferramentas externas, como Docker, AWS, Azure, além de várias opções de SAST como SonarCloud. Entretanto, para algumas funcionalidades avançadas, pode ser necessário utilizar ferramentas externas.

   - **Jenkins**:  
     Jenkins é altamente extensível graças a sua vasta biblioteca de plugins. Ele se integra com praticamente qualquer ferramenta de controle de versão, automação de testes, SAST, e plataformas de cloud como AWS, Google Cloud e Azure. Porém, essas integrações muitas vezes exigem configuração manual.

   - **CircleCI**:  
     CircleCI se destaca pela integração direta com GitHub e GitLab, simplificando a automação dos pipelines. Além disso, ele oferece suporte para integração com Docker, Kubernetes e várias plataformas de cloud, mas pode ter limitações para configurações mais complexas comparado ao Jenkins.

---

3. **Custo**:
   - **GitLab**:  
     O GitLab oferece uma versão gratuita robusta, com suporte para repositórios privados e pipelines CI/CD. As versões pagas incluem recursos adicionais, como segurança avançada e análise de código. É uma solução acessível para pequenas e médias empresas, mas o custo pode aumentar para grandes equipes que precisem de funcionalidades premium.

   - **GitHub**:  
     O plano gratuito do GitHub é generoso, incluindo repositórios privados e GitHub Actions com um limite razoável de minutos de execução de CI/CD. Planos pagos são baseados no uso e são competitivos, especialmente para empresas que não necessitam de integrações muito complexas.

   - **Jenkins**:  
     Sendo open-source, o Jenkins não possui custos de licenciamento. No entanto, os custos de infraestrutura, configuração e manutenção devem ser considerados, principalmente para empresas que precisam de servidores dedicados para rodar os pipelines.

   - **CircleCI**:  
     O CircleCI possui um modelo baseado em consumo de minutos de execução. A versão gratuita é limitada em termos de uso, e para projetos maiores, pode se tornar uma solução mais cara em comparação a opções open-source como Jenkins.

---

4. **Comunidade e Suporte**:
   - **GitLab**:  
     A comunidade do GitLab está em constante crescimento, com um bom suporte oficial e uma ampla documentação. Há fóruns, tutoriais e uma comunidade ativa que contribui com soluções para diversos problemas, embora não seja tão grande quanto a do GitHub.

   - **GitHub**:  
     O GitHub possui uma das maiores comunidades de desenvolvedores do mundo. A plataforma oferece uma excelente documentação e suporte tanto oficial quanto da comunidade. Além disso, a vasta base de usuários significa que praticamente qualquer problema tem solução ou referência disponível online.

   - **Jenkins**:  
     Sendo uma das ferramentas de CI/CD mais maduras e utilizadas, o Jenkins tem uma enorme comunidade, com milhares de plugins desenvolvidos por terceiros. A documentação é extensa, mas pode ser complexa devido à quantidade de configurações possíveis. Há fóruns e grupos de suporte ativos, mas a curva de aprendizado pode ser alta para quem é novo.

   - **CircleCI**:  
     O CircleCI possui uma comunidade ativa, mas menor em comparação ao GitHub e Jenkins. O suporte oficial é bem avaliado, e a documentação é clara e acessível. No entanto, por ser uma plataforma mais fechada, algumas soluções específicas podem ser mais difíceis de encontrar fora da documentação oficial.

---

### Integração com Ferramentas de Teste e Segurança:

1. **Ferramentas de Teste**:
   - **Caixa Branca**:  
     Testes de caixa branca envolvem a análise interna do código, como testes unitários, integração e de segurança de código. Aqui estão alguns exemplos de como integrar ferramentas de caixa branca com as plataformas selecionadas:
     - **GitLab**: O GitLab permite a integração com ferramentas de teste como JUnit e NUnit diretamente no pipeline CI. Testes de unidade e integração podem ser automatizados no GitLab CI, com relatórios detalhados de cobertura de código.
     - **GitHub**: Com o **GitHub Actions**, você pode integrar ferramentas de teste como Jest, Mocha e PyTest. As execuções de testes podem ser acionadas automaticamente em cada pull request, garantindo que as alterações no código não quebrem funcionalidades.
     - **Jenkins**: Jenkins oferece suporte a várias ferramentas de testes de caixa branca como JUnit, NUnit, e TestNG, que podem ser integradas através de plugins. A flexibilidade do Jenkins permite que os testes sejam executados em diversas fases do pipeline.
     - **CircleCI**: O CircleCI possui suporte direto para várias ferramentas de testes de caixa branca, como JUnit, Mocha e PHPUnit. Essas ferramentas podem ser integradas aos workflows do CircleCI com configuração mínima, e os resultados dos testes são exibidos diretamente na interface.

   - **Caixa Preta**:  
     Testes de caixa preta avaliam a funcionalidade do software sem examinar o código-fonte, como testes de aceitação e testes funcionais. Exemplos de integração:
     - **GitLab**: No GitLab, ferramentas de automação de testes funcionais como Selenium podem ser configuradas para rodar em pipelines, permitindo testes automatizados de interfaces web ou APIs.
     - **GitHub**: No **GitHub Actions**, você pode integrar o Selenium, Cypress ou Postman para executar testes de caixa preta diretamente no CI/CD pipeline. Esses testes podem ser agendados para rodar automaticamente em cada nova versão ou pull request.
     - **Jenkins**: Jenkins é amplamente usado para automação de testes funcionais com Selenium, Robot Framework e outras ferramentas de automação. A flexibilidade dos plugins do Jenkins facilita a execução desses testes em paralelo com outros processos do pipeline.
     - **CircleCI**: CircleCI suporta ferramentas como Cypress e Selenium para testes de caixa preta, possibilitando rodar testes funcionais automatizados que avaliam a interface e a experiência do usuário.

---

2. **Ferramentas de Análise de Segurança (SAST)**:
   - **SonarCloud**:  
     - **GitLab**: O SonarCloud pode ser integrado ao **GitLab CI** para executar automaticamente a análise de código estático (SAST) durante o processo de CI. Isso ajuda a identificar vulnerabilidades e problemas de qualidade de código antes do deploy. É possível visualizar os resultados diretamente no GitLab, com links para detalhes no SonarCloud.
     - **GitHub**: O **GitHub Actions** suporta integração com o SonarCloud, permitindo que a análise de código estático seja executada automaticamente durante a execução dos workflows. Os resultados podem ser acessados através do repositório do GitHub, facilitando a análise de segurança e qualidade em cada pull request.
     - **Jenkins**: Com o **SonarQube Scanner Plugin** ou via integração manual, o Jenkins pode rodar o SonarCloud para verificar a qualidade e segurança do código. As análises podem ser automatizadas no pipeline, gerando relatórios detalhados sobre vulnerabilidades e boas práticas de codificação.
     - **CircleCI**: CircleCI permite fácil integração com o SonarCloud por meio de configurações no arquivo `.circleci/config.yml`. A análise de SAST é realizada automaticamente como parte dos workflows de CI, oferecendo visibilidade dos problemas de segurança diretamente na interface do SonarCloud.

   - **SonarQube**:  
     - **GitLab**: O SonarQube pode ser integrado diretamente ao GitLab CI para realizar análises de segurança e qualidade do código durante o processo de CI/CD. O GitLab permite configurar os pipelines para executar o SonarQube em momentos específicos e exibir os relatórios dentro da interface do GitLab.
     - **GitHub**: Com **GitHub Actions**, é possível configurar o SonarQube para rodar como parte dos workflows. Ao integrar SonarQube, a análise de segurança (SAST) é executada automaticamente durante o CI, com relatórios acessíveis no painel do SonarQube ou no próprio GitHub.
     - **Jenkins**: O **Jenkins** é uma das ferramentas mais utilizadas para integração com SonarQube. Utilizando o plugin **SonarQube Scanner**, os pipelines podem executar análises de qualidade de código e segurança com base nas regras configuradas no SonarQube. Relatórios detalhados são gerados a cada build.
     - **CircleCI**: No CircleCI, o SonarQube pode ser integrado usando containers Docker ou chamadas API para realizar análise estática durante o CI. Isso permite que os desenvolvedores vejam problemas de segurança e código imediatamente após os builds, automatizando a detecção de vulnerabilidades.

---

### Avaliação Final e Recomendação:

Após avaliar as ferramentas GitLab, GitHub, Jenkins e CircleCI com base nos critérios estabelecidos, é importante destacar que a escolha da solução ideal depende fortemente do contexto do projeto e dos objetivos da empresa ou equipe. Cada ferramenta tem suas vantagens, e a decisão final deve considerar fatores como custo, produtividade, facilidade de uso e necessidades específicas do projeto.

- **Contexto da Empresa ou Projeto**:  
  Para empresas que buscam reduzir custos, ferramentas como **Jenkins** se destacam por serem open-source e altamente configuráveis, embora exijam mais esforço na configuração e manutenção. Por outro lado, se a prioridade é a praticidade e rapidez na implementação, plataformas como **CircleCI** ou **GitHub Actions** podem ser mais adequadas, pois oferecem fluxos de trabalho prontos e fáceis de configurar. Além disso, à medida que a empresa cresce, a necessidade de planos pagos do **GitLab** e **GitHub** pode se tornar inevitável, especialmente para projetos privados e para obter mais tempo de execução em pipelines de CI/CD.

- **Recomendação para Projetos Acadêmicos**:  
  Para um contexto de faculdade, a escolha da ferramenta também depende do que se busca aprender ou experimentar. Se o objetivo é ganhar experiência com uma solução mais flexível e complexa, o **Jenkins** seria a melhor escolha para CI/CD, pois oferece um nível mais profundo de personalização e integração. Entretanto, se a simplicidade e rapidez são mais importantes, o **CircleCI** seria uma alternativa viável, oferecendo uma curva de aprendizado menor e configurações mais rápidas.

- **Controle de Versão**:  
  Entre **GitHub** e **GitLab**, a escolha pode variar conforme o uso e familiaridade. Para um projeto de faculdade ou para aqueles que já estão acostumados com o GitHub, ele é uma escolha sólida, devido à sua popularidade, grande base de usuários e recursos extras, como Kanban boards e pull requests para revisões de código. No entanto, para quem deseja explorar algo novo e conhecer uma plataforma diferente, o **GitLab** oferece uma solução integrada com CI/CD e outras funcionalidades avançadas.

- **Recomendação**:  
  Com base nos critérios avaliados e no contexto de um projeto acadêmico, recomendamos o **GitHub** para controle de versão devido à sua facilidade de uso, popularidade e recursos extras. Para o ambiente de CI/CD, recomendamos o **Jenkins** para quem deseja aprender e se aventurar em uma solução mais flexível e personalizável, ou **CircleCI** para quem busca praticidade e rapidez na implementação.

---

## 4. Desenvolvimento de um Pipeline de CI/CD (17/09 a 23/09)

### Diagrama do Pipeline de CI/CD:

- Link para o diagrama: https://miro.com/app/board/uXjVLcSDyos=/?share_link_id=101619001006

![alt text](<CI_CD Diagram - Frame 1.jpg>)

---
