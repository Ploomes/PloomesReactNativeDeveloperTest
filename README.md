# PloomesReactNativeDeveloperTest

## Bem vindo a Ploomes! (vc tá quase lá!)

<p>Parabéns! Vc chegou no ponto mais importante do nosso processo seletivo. Aqui na Ploomes nos REALMENTE acreditamos que precisamos de pessoas incríveis para ter um produto incrível. Se você poderia trabalhar nas maiores empresas do mundo, queremos que vc escolha trabalhar conosco!<p>
  
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

### O que fazer?

Na Ploomes precisamos lidar com formularios, campos de formulários, campos padrão, campos dinâmicos... Enfim, uma infinitude campo (Fields), formulários (Forms) e campos de formulários (FormFields). Seu trabalho será lidar com essas 3 entidades. 

Queremos que vc crie uma aplicação capaz de renderizar um formulário Ploomes e criar/editar uma entidade dentro da nossa aplicação. Parece suuuper simples (de certa forma é) mas tem alguns detalhes:

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
