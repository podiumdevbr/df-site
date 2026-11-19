# DataFacil Compliance

### Site institucional · Privacidade, proteção de dados e conformidade no setor educacional

> **Privacidade e proteção de dados como pilares de confiança e
> excelência na educação.**

![Status](https://img.shields.io/badge/status-em%20planejamento-C5A253?style=flat-square)
![Stack](https://img.shields.io/badge/stack-JavaScript%20%7C%20Node.js-171717?style=flat-square)
![Foco](https://img.shields.io/badge/foco-setor%20educacional-C5A253?style=flat-square)

------------------------------------------------------------------------

## 1. Visão do projeto

Desenvolver o site institucional da **DataFacil Compliance**, empresa
dedicada à auditoria, consultoria, governança e adequação em privacidade
e proteção de dados, com foco prioritário em escolas particulares e
instituições de ensino.

O site deverá comunicar autoridade técnica, confiança, clareza e
capacidade de traduzir requisitos de privacidade em práticas aplicáveis
à rotina escolar.

Este repositório será a referência central para decisões de produto,
identidade visual, arquitetura, conteúdo, segurança e evolução técnica.

### Objetivos

-   Apresentar a DataFacil Compliance e seu posicionamento.
-   Explicar serviços e soluções de forma clara e orientada às
    necessidades das instituições de ensino.
-   Demonstrar metodologia, conhecimento técnico e compreensão dos
    fluxos escolares.
-   Gerar contatos comerciais qualificados, sem coletar dados
    excessivos.
-   Publicar conteúdos educativos sobre privacidade e proteção de dados.
-   Estabelecer uma base técnica segura, acessível, responsiva e
    sustentável.

## 2. Público e posicionamento

### Público prioritário

-   Mantenedores e proprietários de escolas particulares.
-   Diretores e gestores escolares.
-   Coordenadores administrativos e pedagógicos.
-   Profissionais de tecnologia, jurídico, compliance e proteção de
    dados.
-   Responsáveis por processos de matrícula, atendimento, comunicação e
    gestão escolar.

### Posicionamento

A DataFacil Compliance deve ser apresentada como uma parceira
especializada que compreende tanto os requisitos de privacidade e
proteção de dados quanto a realidade operacional das instituições de
ensino.

A comunicação deve evitar alarmismo, promessas absolutas de conformidade
ou afirmações de que a contratação de um serviço, isoladamente, garante
adequação integral à legislação.

## 3. Identidade visual

### Direção criativa

**Dark institucional premium**, com preto profundo como base, dourado
metálico inspirado na logomarca e tons claros para leitura e contraste.

A marca enviada apresenta um símbolo geométrico tridimensional com
aparência de metal trabalhado. O acabamento visual combina reflexos de
ouro claro, champagne, bronze e ouro envelhecido. A identidade não deve
ser reduzida a um amarelo-dourado chapado.

A referência tipográfica disponível sugere letras maiúsculas, serifadas,
com espaçamento entre caracteres e linguagem institucional clássica. A
definição da família tipográfica final dependerá de testes de
legibilidade e compatibilidade com a marca em alta resolução.

### Paleta inicial de referência

Os valores abaixo são tokens provisórios para orientar os primeiros
protótipos. Não representam uma extração colorimétrica definitiva dos
arquivos de imagem.

  Token                  Cor         Uso
  ---------------------- ----------- ---------------------------------
  `--color-black`        `#090909`   Fundo principal
  `--color-black-soft`   `#141414`   Seções e superfícies escuras
  `--color-surface`      `#1D1B18`   Cards, menus e painéis
  `--gold-light`         `#F1D99A`   Reflexos e detalhes claros
  `--gold-champagne`     `#D9BD7A`   Destaques metálicos
  `--gold`               `#B58A3A`   Elementos de marca
  `--gold-bronze`        `#80602D`   Sombras e profundidade
  `--color-white`        `#F5F3EE`   Texto principal e fundos claros
  `--color-muted`        `#B8B3A8`   Texto secundário

### Aplicação do dourado metálico

O dourado deverá ser construído por combinações sutis de tons,
gradientes e, quando adequado, reflexos e sombras. Exemplo conceitual:

``` css
:root {
  --gold-metallic: linear-gradient(
    115deg,
    #80602D 0%,
    #D9BD7A 24%,
    #F1D99A 42%,
    #A77B32 62%,
    #E2C987 82%,
    #80602D 100%
  );
}
```

O gradiente é uma referência de acabamento para elementos gráficos,
títulos selecionados e detalhes decorativos. Não deverá ser aplicado
indiscriminadamente em textos longos, controles ou elementos que
prejudiquem a leitura.

### Tipografia

Diretriz inicial:

-   **Marca e títulos institucionais:** fonte serifada elegante,
    preferencialmente com caixa alta e espaçamento controlado.
-   **Textos, navegação e interfaces:** fonte sem serifa, moderna e de
    alta legibilidade.
-   **Hierarquia:** títulos expressivos, subtítulos objetivos e
    parágrafos confortáveis para leitura.

A escolha definitiva das fontes será validada em desktop e dispositivos
móveis. A tipografia do logotipo não deverá ser recriada ou substituída
sem necessidade.

### Uso da logomarca

-   Preservar proporções, geometria e cores originais.
-   Não distorcer, inclinar, aplicar filtros agressivos ou reconstruir o
    símbolo automaticamente.
-   Preferir arquivo vetorial ou imagem de alta resolução quando
    disponibilizado.
-   Preparar versões adequadas para fundos escuros e claros, caso
    existam arquivos oficiais.
-   Manter área de respiro ao redor do símbolo.
-   Usar o símbolo isolado como favicon somente após preparar uma versão
    apropriada.

**Arquivos de marca:** armazenar em `public/assets/brand/`. Os arquivos
enviados na conversa ainda deverão ser incorporados ao repositório, com
nomes e formatos definitivos.

## 4. Estrutura de páginas e conteúdo

A arquitetura de informação inicial será:

  -----------------------------------------------------------------------
  Página/seção                        Finalidade
  ----------------------------------- -----------------------------------
  Início                              Apresentar proposta de valor,
                                      diferenciais e chamadas para
                                      contato

  Sobre a DataFacil                   História, propósito, visão, valores
                                      e posicionamento

  Soluções                            Auditoria, consultoria, governança,
                                      adequação e capacitação

  Setor educacional                   Desafios e fluxos de privacidade na
                                      realidade escolar

  Metodologia                         Etapas de diagnóstico,
                                      planejamento, implementação e
                                      acompanhamento

  Conteúdos                           Artigos, materiais educativos e
                                      orientações

  Contato                             Canal institucional para
                                      solicitações comerciais

  Política de Privacidade             Informações sobre o tratamento de
                                      dados no próprio site

  Política de Cookies                 Informações sobre cookies e
                                      tecnologias semelhantes, quando
                                      aplicável
  -----------------------------------------------------------------------

A navegação poderá ser ajustada durante a etapa de UX. Não publicar
serviços, certificações, resultados, clientes ou credenciais que ainda
não tenham sido confirmados pela empresa.

### Diretrizes de conteúdo para o setor educacional

A comunicação deverá considerar, entre outros aspectos:

-   Dados de crianças e adolescentes e seu melhor interesse.
-   Relação entre escola, estudantes, responsáveis, colaboradores e
    fornecedores.
-   Processos de matrícula, rematrícula, secretaria, atividades
    pedagógicas e comunicação.
-   Imagens, vídeos, registros acadêmicos e informações de saúde
    eventualmente tratados pela instituição.
-   Controle de acesso, compartilhamento, retenção e descarte de
    informações.
-   Gestão de operadores, contratos, fornecedores e incidentes.
-   Capacitação e cultura de privacidade no ambiente escolar.

O conteúdo deverá distinguir obrigações legais, boas práticas,
recomendações técnicas e decisões que dependem de análise contextual.

## 5. Diretrizes de UX e interface

-   Design responsivo, com abordagem mobile-first.
-   Navegação simples, previsível e consistente.
-   Cabeçalho institucional com logomarca, menu e chamada para ação.
-   Hierarquia visual clara e textos objetivos.
-   Animações discretas, sem comprometer desempenho ou acessibilidade.
-   Estados visuais de foco, hover, carregamento, sucesso e erro.
-   Formulários curtos e com finalidade explícita.
-   Contraste e legibilidade verificados, inclusive nos elementos
    dourados.
-   Respeito à preferência por movimento reduzido
    (`prefers-reduced-motion`).
-   HTML semântico e navegação por teclado.

## 6. Arquitetura e tecnologias

### Stack definida

  Tecnologia           Responsabilidade
  -------------------- ---------------------------------------------
  HTML5                Estrutura semântica e acessível
  Tailwind CSS         Estilização e responsividade
  JavaScript moderno   Interatividade no navegador
  Node.js              Processamento no servidor quando necessário
  Git e GitHub         Versionamento, colaboração e histórico

**Diretriz:** utilizar JavaScript como linguagem predominante no
front-end e no back-end. PHP não faz parte da arquitetura inicial.

### Estratégia de implementação

O site começará com uma estrutura institucional simples, evitando
dependências e serviços desnecessários.

O back-end Node.js será introduzido para funcionalidades que realmente
precisem de processamento no servidor, como recebimento de formulários,
validações, integração com serviços e envio de notificações.

Segredos, credenciais e chaves de integração nunca deverão ser expostos
no código enviado ao navegador ou versionados no GitHub.

A escolha de hospedagem deverá considerar suporte a Node.js, HTTPS,
variáveis de ambiente, logs, backups e possibilidade de evolução.

### Estrutura de diretórios proposta

``` text
datafacil-compliance/
├── public/
│   ├── assets/
│   │   ├── brand/
│   │   ├── images/
│   │   ├── icons/
│   │   └── fonts/
│   └── favicon.ico
├── src/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── main.js
│   └── components/
├── server/
│   ├── app.js
│   ├── routes/
│   ├── controllers/
│   └── middleware/
├── index.html
├── package.json
├── .env.example
├── .gitignore
└── README.md
```

Esta é a estrutura de referência inicial. Pastas e módulos poderão ser
ajustados conforme as funcionalidades efetivamente implementadas. Não
criar banco de dados antes de existir requisito concreto que o
justifique.

## 7. Privacidade, proteção de dados e segurança

O próprio site deverá refletir os princípios que a DataFacil Compliance
comunica a seus clientes.

### Privacy by Design e Privacy by Default

-   Definir finalidade e necessidade antes de criar cada campo ou
    funcionalidade.
-   Coletar somente os dados necessários para a finalidade informada.
-   Não solicitar dados de estudantes ou crianças em formulários
    comerciais.
-   Apresentar avisos de privacidade próximos aos pontos de coleta.
-   Definir retenção, acesso e descarte dos dados recebidos.
-   Utilizar configurações iniciais mais protetivas à privacidade.
-   Avaliar cookies, analytics, pixels e integrações antes de ativá-los.
-   Não presumir que a simples exibição de um banner de cookies torna o
    tratamento regular.

### Segurança de entradas e formulários

Todo dado recebido deverá ser considerado não confiável.

-   Validação de tipo, formato, tamanho e conteúdo no servidor.
-   Codificação/escape contextual na saída para prevenir XSS.
-   Manipulação segura do DOM, evitando `innerHTML` com conteúdo não
    confiável.
-   Proteção CSRF quando aplicável à arquitetura e ao fluxo.
-   Rate limiting, honeypot e controles de origem como camadas
    complementares, sem tratá-los como substitutos de autenticação ou
    validação.
-   Mensagens de erro que não revelem detalhes internos.
-   Logs sem exposição desnecessária de dados pessoais ou segredos.
-   HTTPS em produção e cabeçalhos de segurança adequados.

### Banco de dados e integrações

Se um banco de dados for adotado:

-   Utilizar consultas parametrizadas/prepared statements.
-   Aplicar menor privilégio às credenciais.
-   Validar e controlar acesso a cada operação.
-   Não armazenar dados sensíveis sem necessidade e avaliação
    específica.
-   Definir política de retenção e rotina de backup.

Se houver integração com IA no futuro, entradas de usuários deverão ser
tratadas como dados não confiáveis, com validação, limites, isolamento
de instruções e controles contra prompt injection. Nenhuma entrada livre
deverá ser encaminhada diretamente a um prompt sem salvaguardas.

### Referenciais normativos

O projeto deverá considerar, conforme aplicabilidade e análise do caso
concreto:

-   Lei Geral de Proteção de Dados Pessoais --- LGPD (Lei nº
    13.709/2018).
-   Estatuto da Criança e do Adolescente --- ECA.
-   Normas, resoluções, guias e orientações da ANPD.
-   ECA Digital e sua regulamentação aplicável.
-   GDPR, quando houver hipótese de aplicação territorial ou material.
-   Requisitos de acessibilidade e segurança pertinentes ao serviço.

A implementação técnica não equivale, isoladamente, a uma certificação
ou garantia de conformidade jurídica. Textos legais, bases legais,
prazos de retenção e mecanismos de consentimento deverão ser validados
de acordo com as operações reais da DataFacil Compliance.

## 8. Formulário de contato

O formulário comercial deverá ser direcionado a representantes e
profissionais das instituições, com coleta mínima.

Campos candidatos, sujeitos à validação da finalidade:

-   Nome do contato.
-   E-mail profissional.
-   Instituição de ensino.
-   Assunto ou serviço de interesse.
-   Mensagem, com orientação para não inserir dados pessoais de
    estudantes ou informações sensíveis.

Antes da implementação, definir:

-   Finalidade e hipótese legal adequada para cada tratamento.
-   Texto de aviso de privacidade.
-   Destinatários e operadores envolvidos.
-   Canal para exercício de direitos.
-   Prazo de retenção e procedimento de descarte.
-   Proteções técnicas, controles antiabuso e fluxo de atendimento.

O envio do formulário não deverá ser condicionado a consentimento
genérico para marketing. Eventual comunicação promocional deverá ter
finalidade, fundamento e mecanismo próprios, quando aplicáveis.

## 9. Desempenho, acessibilidade e qualidade

Metas de engenharia:

-   Carregamento eficiente e otimização de imagens.
-   CSS e JavaScript enxutos, com carregamento adequado.
-   Evitar bibliotecas e scripts de terceiros sem justificativa.
-   Imagens com dimensões definidas, formatos modernos e texto
    alternativo quando pertinente.
-   HTML semântico, labels e mensagens de erro acessíveis.
-   Navegação integral por teclado.
-   Contraste compatível com WCAG 2.2 AA como referência de qualidade.
-   Testes em navegadores e larguras de tela relevantes.
-   Verificação de links, metadados, título e descrição de páginas.
-   Monitoramento de erros sem coleta excessiva de dados.

## 10. SEO e presença institucional

-   Títulos e descrições únicos por página.
-   URLs legíveis e estrutura de headings coerente.
-   Conteúdo original e útil para gestores escolares.
-   Metadados Open Graph para compartilhamento.
-   Favicon e identidade consistente.
-   Sitemap e `robots.txt` quando o site estiver pronto para publicação.
-   Dados estruturados somente quando corretos e aplicáveis.
-   Estratégia editorial alinhada às dúvidas reais do setor educacional.

## 11. Hospedagem e publicação

A hospedagem ainda não foi contratada.

Critérios para seleção:

-   Compatibilidade com Node.js na versão suportada pelo projeto.
-   Certificado TLS/HTTPS.
-   Configuração de variáveis de ambiente.
-   Logs e monitoramento.
-   Backups e possibilidade de restauração.
-   Política clara de segurança e tratamento de dados do provedor.
-   Facilidade de integração com GitHub e fluxo de deploy.
-   Custo compatível com o estágio do projeto.

O domínio, provedor e ambiente de produção serão definidos antes da
publicação. Não inserir credenciais ou arquivos `.env` no repositório.

## 12. Etapas de desenvolvimento

-   [ ] **Etapa 1 --- Fundação:** validar identidade visual, README,
    estrutura do repositório e ferramentas.
-   [ ] **Etapa 2 --- Design:** definir tipografia, tokens, grid,
    componentes e protótipo da página inicial.
-   [ ] **Etapa 3 --- Home:** desenvolver cabeçalho, hero, proposta de
    valor, soluções, segmentos, metodologia e chamadas para contato.
-   [ ] **Etapa 4 --- Páginas institucionais:** sobre, soluções, setor
    educacional, metodologia e contato.
-   [ ] **Etapa 5 --- Conteúdo e políticas:** conteúdos educativos e
    documentos de privacidade do próprio site.
-   [ ] **Etapa 6 --- Back-end:** implementar formulário e integrações
    necessárias em Node.js.
-   [ ] **Etapa 7 --- Qualidade:** testes funcionais, responsividade,
    acessibilidade, desempenho e segurança.
-   [ ] **Etapa 8 --- Publicação:** escolher hospedagem, configurar
    domínio, HTTPS, ambiente e deploy.
-   [ ] **Etapa 9 --- Evolução:** monitoramento, manutenção e melhorias
    contínuas.

## 13. Convenções de desenvolvimento

-   Utilizar nomes de arquivos e variáveis claros e consistentes.
-   Preferir componentes e módulos reutilizáveis.
-   Manter separação entre apresentação, lógica de interface e
    processamento no servidor.
-   Não versionar segredos, credenciais, dados pessoais ou arquivos
    temporários.
-   Registrar mudanças relevantes no histórico Git.
-   Documentar dependências, comandos e decisões de arquitetura.
-   Não adicionar dependências sem necessidade técnica identificável.
-   Atualizar este README quando decisões estruturais forem alteradas.

### Variáveis de ambiente

O arquivo `.env` deverá permanecer fora do versionamento. O
`.env.example` deverá conter apenas nomes e exemplos fictícios de
variáveis, nunca credenciais reais.

## 14. Critérios de conclusão

Uma entrega será considerada pronta para publicação quando:

1.  O conteúdo institucional tiver sido revisado e aprovado.
2.  A identidade visual estiver coerente com a logomarca oficial.
3.  As páginas funcionarem em dispositivos móveis e desktop.
4.  Formulários e integrações tiverem validação e proteção no servidor.
5.  Avisos e políticas refletirem os tratamentos efetivamente
    realizados.
6.  Não houver segredos ou dados pessoais indevidos no repositório.
7.  Os testes essenciais de acessibilidade, segurança e funcionamento
    tiverem sido executados.
8.  O ambiente de produção estiver configurado com HTTPS, logs e
    procedimentos de manutenção.

------------------------------------------------------------------------

## 15. Princípio orientador

> **Tecnologia, governança e privacidade a serviço de uma educação mais
> segura e confiável.**

O site da DataFacil Compliance não deverá ser apenas uma vitrine
comercial. Ele deverá expressar, na própria experiência digital, os
valores de responsabilidade, transparência, segurança e respeito às
pessoas que fundamentam o trabalho da empresa.

------------------------------------------------------------------------

**DataFacil Compliance**\
*Auditoria · Consultoria · Governança · Privacidade e Proteção de Dados*

`<sub>`{=html}Documento de especificação inicial --- sujeito à evolução
conforme decisões de negócio, validações técnicas e requisitos efetivos
do projeto.`</sub>`{=html}
