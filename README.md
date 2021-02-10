# PloomesReactNativeDeveloperTest

## Bem vindo a Ploomes! ( Vc está quase lá...digo...aqui! )

<p>Parabéns! Vc chegou no ponto mais importante do nosso processo seletivo. Aqui na Ploomes nos REALMENTE acreditamos que precisamos de pessoas incríveis para ter um produto incrível. Se você tem potencial para trabalhar nas maiores empresas de tecnologia do mundo, queremos que vc escolha trabalhar conosco!<p>
  
Agora é a sua oportunidade de nos mostrar que tem essa capacidade  "World Class". 

Somos guiados por uma mentalidade assim:

```TS
  
  interface IDeveloper {
    hasBloodInTheEyes: boolean // motivation prop;
    skill: 'meh' | 'rookie' | 'default' | 'good' | 'very_good' | 'world_class_developer'; // skill prop
    ambicious: boolean; // cultural prop
    knows_json_is_not_JASON: boolean // mental status prop 
  }

  function developerTest( developer: TDeveloper ){
    const { hasBloodInTheEyes, skills, ambicious, knows_json_is_not_JASON } = developer //lets deconstruct this developer!
    
    if(hasBloodInTheEyes && ambicious){
      /* We take our culture very seriously 
        and want motivated people working with us, 
        its what keeps us motivated :D 
      */
      
      if( skill === 'world_class_developer' ){
        /* 
            "We don't know who you are (yet). We kinda know what you want. 
            So we want to know if you have a very particular set of skills. 
            Skills you have acquired over a (very long) career. 
            Skills that make you a nightmare for BUGS like we have. "

            BTW, I hope you got this reference, otherwise I'm just being weird.
        */
        return 'Welcome at Ploomes'
      }
    }
    return 'Better luck next time :D'
  }
````

Bonus question: Pq o código acima não compila?

# Tarefa

Chega de conversa, esses são os detalhes da tarefa que queremos ver você realizando 

- [O que fazer?](#0-que-fazer-?)
- [Prazo](#prazo)
- [Material de Apoio](#Material-de-Apoio)
- [Ferramentas Sugeridas](#Ferramentas-Sugeridas)
- [Ajuda](#Ajuda)

### O que fazer?

Na Ploomes precisamos lidar com formularios, campos de formulários, campos padrão, campos dinâmicos... Enfim, uma infinitude campos [Fields](https://ploomes.github.io/PloomesDocs/content/fields/), [formulários](https://ploomes.github.io/PloomesDocs/content/forms/) e [campos de formulários](https://ploomes.github.io/PloomesDocs/content/fields/). Seu trabalho será lidar com essas 3 entidades. 

Queremos que vc crie uma aplicação capaz de renderizar um formulário Ploomes e criar/editar uma [entidade](https://ploomes.github.io/PloomesDocs/content/entities/) dentro da nossa aplicação. Parece suuuper simples (de certa forma é) mas tem alguns detalhes.

#### Requisítos mínimos

 - Aplicação React Native usando Typescript (we LOVE Typescript S2) ou Javascript
 - Criar uma aplicação que retorne um formulário de Contato de acordo com o configurado na sua conta. 
 - O formulário pode conter apenas campos padrão, mas deve conter pelo menos 5 tipos de campos diferentes. 
 - Função de criação e edição de um contato da sua conta. (O mesmo componente deve realizar ambas ações)
 
#### Requisítos 'Quero fazer mais'

Todos os requisitos acima e:

 - Usar Typescript.
 - Ter campos dinâmicos no formulário.
 - Utilizar o componente criado para a leitura (visualização) dos dados de um contato.
 - Pelo menos 7 tipos de campos diferentes
 - Criar o passo de criação 'offline' e verificar a conexão antes de enviar para a API (we're an offline first app)
 
#### Requisítos 'This is SPARTAAAAA!!!' 

Todos os acima e:

 - O Ploomes possui um motor de fórmulas poderoso, configure pelo menos uma fórmula em um dos campos e faça ela funcionar.

### Prazo

O Prazo de conclusão da tarefa é de 7 dias corridos a contar do dia em que iniciar o projeto. Contudo, queremos que sejam abertos caso precisem de um tempo a mais por algum motivo (Transparência é um dos nossos valores culturais!), e vms estudar caso a caso. **Evite entregar a tarefa incompleta**, preferimos extender 2-3 dias e ver o seu melhor do que perdermos a chance de ter um profissional World Class aqui por falta de tempo.

### Material de Apoio
 - [Developers Ploomes](https://developers.ploomes.com/) - ferramenta de teste de chamadas a api.
 - [Coleção de chamadas do Postman](https://www.getpostman.com/collections/33d47e1467a02c860334) - coleção de chamadas a api com exemplos.
 - [PloomesDocs](https://ploomes.github.io/PloomesDocs/) - documentação do Ploomes tipos, relações e exemplos(em construção).
 
### Ferramentas Sugeridas 

#### PloomesTSTypes

Biblioteca com vários tipos relevantes da Ploomes. Caso decida realizar a aplicação em typescript, essa biblioteca será sua melhor amiga.
Veja a [documentação](https://github.com/Ploomes/PloomesTSTypes/blob/master/readme.md).

### Ajuda

Na Ploomes acreditamos no poder do trabalho em equipe, e achamos que isso deveria fazer parte também do processo seletivo. Por isso, você terá a sua disposição **um** slot de de uma hora com um dos membros da nossa equipe para utilizar durante o período de desenvolvimento do projeto (não vamos poder dar feedbacks, apenas ajudar você na compreensão do Ploomes em si). Fique a vontade para decidir qual o melhor momento para usar esse tempo, seja no início, meio ou final da tarefa. Quando estiver pronto para marcar esse horário, mande um email para tiago.provenzano@ploomes.com e marque o horário.
