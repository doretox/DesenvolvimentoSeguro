<p align="center">

<img src="https://cdn0.iconfinder.com/data/icons/business-startup-10/50/8-512.png" width=300 height=300>

</p>

# Fundamentos

### O que é Desenvolvimento Seguro?


### Porque Desenvolvimento Seguro?
Quando falamos de desenvolvimento seguro, é importante pensar em todas as etapas que fazem parte do processo de SDLC:

```
 Requisitos > Design > Desenvolvimento > Testes > Deploy/Produção 
```

A maioria das empresas fazem validações de segurança nas ultimas fases dos projetos, e isso acaba por gerar um custo de correção bem maior do que seria caso as vulnerabilidades fossem tratadas ainda em fase inicial. 
Abaixo temos um gráfico resultado pela NIST que retrata esse cenário, uma vez que fazemos a mitigação desses problemas logo no início, evitamos o retrabalho, aumentamos o nível de maturidade de segurança, e prevenimos possiveis ataques baseados nessas vulnerabilidades. 

<p align="center">
<img src="https://assets.deepsource.io/032e723/images/blog/cost-of-fixing-bugs/chart.jpg" width=680>   
</p>




### Quais os pilares do Desenvolvimento Seguro?


### Por onde começar?

Antes de fornecer treinamentos sobre Desenvolvimento Seguro, e começar a aplicar os conceitos desde o início, é interessante saber o nível de maturidade de segurança do seu ciclo e a partir disso fazer as modificações necessárias para essa melhoria. 
Atualmente temos a OWASP SAMM (OWASP Software Assurance Maturity Model), um projeto mantido pela OWASP que visa ajudar numa avaliação rápida do contexto para entender o nível de maturidade. Ele é composto por algumas perguntas de acordo com cada uma das fases do processo de desenvolvimento:

- **Requisitos** - Durante o momento de construção do seu software, sua equipe tem como princípio realizar o levantamento das necessidade de segurança e privacidade?

- **Design** - Sua equipe, ao iniciar um novo projeto de software, realiza ações para identificar as ameaças as quais o seu software pode estar exposto?

- **Coding** - Existe algum tipo de avaliação do código (Code Review)?

- **Testes** - Durante a fase de testes de sua aplicação, testes estáticos afim de validar os requisitos de segurança definidos são realizados? 

- **Produção** - Quando da operacionalização do seu software, há a realização de pentests para garantir que sua aplicação está protegida?

Com base nos "sim" e "não" das respostas conseguimos ter uma ideia do nível de maturidade do processo, se o "não" for maioria, é importante que o assunto seja levado para discussão. 

### Shift Left 


Shift Left em segurança de aplicações é uma abordagem estratégica que envolve a integração de práticas de segurança desde as fases iniciais do ciclo de vida de desenvolvimento de software (SDLC), em oposição à abordagem tradicional de tratamento de segurança apenas em estágios avançados ou pós-desenvolvimento. O conceito é inspirado no termo "shift left" utilizado em metodologias ágeis, onde a ideia é antecipar e abordar problemas o mais cedo possível no processo de desenvolvimento.

Na prática, isso significa considerar aspectos de segurança desde o início do projeto, durante o planejamento e o design, e continua a integrar práticas de segurança em cada etapa do desenvolvimento, incluindo implementação, testes e implantação.

Por exemplo, em vez de realizar testes de segurança apenas no final do processo de desenvolvimento, a equipe pode incorporar testes de segurança automatizados ao fluxo de trabalho de integração contínua. Isso permite que problemas de segurança sejam identificados e corrigidos rapidamente, antes que o código seja mesclado ao repositório principal.

Outro exemplo seria a utilização de ferramentas de análise estática de código (SAST) para identificar vulnerabilidades de segurança durante a fase de codificação. Ao analisar o código-fonte em busca de padrões conhecidos de vulnerabilidades, os desenvolvedores podem corrigir esses problemas antes mesmo que o código seja submetido ao controle de versão.

Além disso, a adoção de revisões de código com foco em segurança, onde os membros da equipe revisam o código uns dos outros em busca de possíveis vulnerabilidades, é uma prática comum no contexto de shift left. Essas revisões ajudam a promover uma cultura de segurança dentro da equipe de desenvolvimento e aumentam a conscientização sobre questões de segurança.

Em resumo, o shift left em segurança de aplicações se concentra em antecipar e abordar preocupações de segurança desde as fases iniciais do desenvolvimento de software, incorporando práticas de segurança em todo o SDLC. Isso resulta em software mais seguro, reduzindo custos e riscos associados à correção de vulnerabilidades descobertas tardiamente no processo de desenvolvimento.
