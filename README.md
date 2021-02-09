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

- [O que fazer](#0-que-fazer-?)

### O que fazer?
