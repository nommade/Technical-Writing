<div align = center>
    <video controls width="800">
        <source src="../src/video/M_1_Aula-3.mp4" type="video/mp4">
    </video>
</div>

# Troubleshooting
Para começar, o que é um troubleshooting (resolução de problemas)?

Um troubleshooting nada mais é do que uma documentação que **lista possíveis erros** que o seu produto pode apresentar e **apresenta as soluções**.

Talvez, só por esse conceito, você se questione: uma vez que encontramos um erro, não poderíamos simplesmente solucionar no produto e não precisar documentar? Sim, com certeza, mas em alguns casos, esse erro pode acontecer por várias razões, inclusive razões que não conhecemos muito bem a causa.

Por exemplo: você tenta fazer uma configuração, ou criar uma conta, ou implementar um tipo de configuração e surge um erro desconhecido, que não é exatamente um problema do produto. Às vezes, foi só naquela configuração que apresentou um erro atípico, mas que já sabemos como solucionar.

Se esse for o caso da empresa em que você trabalha e do produto que está sendo documentado, é muito interessante que você faça uso dessa prática e crie troubleshootings para esclarecer para o seu público como ele pode solucionar esse possível erro.

Ao escrever o troubleshooting e antecipar a dor da pessoa usuária, possibilitamos que ela consiga resolver o problema e tenha a solução que procura.

<br/>

## Tópicos para estruturar um troubleshooting
Em resumo, temos um problema, que geralmente é o título do troubleshooting, ou o título pode ser "Troubleshooting" e os tópicos podem ser cada um dos problemas listados.

Na sequência, temos a solução e a questão dos links relacionados, porque, geralmente, um troubleshooting fica hospedado em uma seção de suporte, ou mesmo que seja na documentação de produto, entre outros menus existentes no portal da documentação, ele estará em uma seção específica chamada "Troubleshooting" ou algum nome similar.

Temos várias opções: podemos separar um problema específico em cada documentação; ou, a depender da quantidade de problemas que listados no troubleshooting, pode ser uma única documentação por extenso, com cada um dos problemas mapeados.

Porém, pode ser que você precise fazer alguma referência a outro conteúdo. Se esse for o caso, você pode aproveitar a seção de links relacionados para fazê-lo.

<br/>

## Fontes de troubleshooting
Onde podemos buscar fontes para esse troubleshooting? Onde encontramos esses possíveis erros para montar a documentação?

O primeiro deles é o ticket de suporte, ou de incoming de produto. Às vezes, podemos entrar em contato com a equipe de suporte ou de atendimento ao cliente, e descobrir em conjunto com eles que existem tickets abertos para problemas muito parecidos.

A depender desse ticket aberto e reportado, podemos encontrar uma oportunidade de isso virar um troubleshooting. Assim, quando a equipe de suporte receber um caso similar, haverá o troubleshooting como base para resolver esse caso e direcionar a pessoa usuária para essa documentação com mais detalhes.

Outra fonte igualmente importante é de feedbacks das pessoas usuárias. A depender da empresa onde você trabalha, pode ser que esse feedback seja interno, porque você escreve documentação para dentro da empresa, dentro da sua equipe, ou para outras equipes consumirem.

Nesse caso, pode ser que feedbacks dessas pessoas te ajudem a entender qual é uma dúvida frequente, um erro frequente, e que você pode aproveitar para escrever um troubleshooting sobre.

Se for o caso de público externo, você pode receber esses feedbacks através de componentes de feedback. Sabe quando encontramos ícones de thumbs up e thumbs down em uma documentação para dizer se aquilo foi útil, ou deixar um feedback escrito sobre o que poderia ser melhor? Essas também podem ser fontes de análise e estudo para avaliar se existe conteúdo potencial para escrever um troubleshooting.

Além disso, outra fonte para você estruturar o seu troubleshooting são testes no produto. Algo pode ter escapado, mesmo tendo passado pelo teste de QA, por exemplo, toda a parte de testes automatizados para verificar se o produto funciona 100% antes de ser lançado.

A depender do erro encontrado em alguns testes de produto, pode surgir uma oportunidade de fazer um troubleshooting para deixar isso documentado e visível na documentação, no portal, no site de documentação. Assim, a pessoa usuária sabe que isso está mapeado, e caso ela tenha esse problema, já está identificado.

Essas são algumas possibilidades de fontes com potencial para encontrar insumo, conteúdo e insights para escrever um troubleshooting.

<br/>

## Analisando exemplos práticos
Para tornar isso ainda mais tangível, vamos analisar alguns exemplos práticos.

O primeiro exemplo é do próprio Google, na página do Google Cloud. Neste caso, acessaremos a seção "[Chrome Insider: Troubleshooting with Chrome Browser](https://cloud.google.com/blog/products/chrome-enterprise/how-to-troubleshoot-common-problems-with-chrome-browser)" do Google Cloud, que fala especificamente sobre resolução de problemas ou troubleshooting. Ao navegar pela página, estão listados vários erros que podemos analisar. Por exemplo:

> ### Solução de problemas no Chrome
>
> Se surgir um problema no navegador Chrome, aqui estão algumas dicas sobre como resolvê-lo. Você pode começar fazendo algumas perguntas importantes:
>
> *O Chrome está com problemas, mas funciona corretamente em uma janela anônima?*
> - Pode ser um problema de extensão. Se possível, tente desativar todas as extensões e testar cada uma delas para identificar o causador do problema.
> - Também pode ser um problema de cache/cookie. Limpe o cache e os cookies e reinicie o navegador. Isso ajudará com quaisquer problemas de estado do aplicativo.

Outro exemplo, dessa vez de uma empresa que chamada StackSpot, é a própria seção "Troubleshooting", onde cada problema é um título.

Temos, por exemplo, "Não consigo aplicar um Plugin no meu Workspace", e em seguida a solução "Teste novamente seguindo os passos abaixo". Ou então, outro problema, "Não consigo aplicar um Plugin no meu Workspace", acompanhado de passo a passo mais descritivo da solução.

Perceba que é literalmente essa estrutura que falamos: um problema, que geralmente é o título; a solução; e a informação detalhada de como essa solução se dá. Assim, resolvemos o problema.

No nosso projeto, também fizemos uma [simulação de troubleshooting](https://github.com/marimoreiratw/projeto-alura/blob/main/troubleshooting.md), imaginando que a pessoa usuária poderia ter problemas em tentar usar os serviços da ByteBank. Elaboramos um troubleshooting muito simples, com o primeiro erro sendo "Erro ao acessar sua conta", acompanhado de suas soluções e alguns links relacionados.

Se quiséssemos continuar essa documentação, poderíamos listar, por exemplo, "Erro ao sacar o meu investimento da carteira", ou então "Erro ao redefinir minha senha". Tudo isso poderia ser erro e poderíamos documentar cada uma dessas soluções no troubleshooting, formando uma seção unificada para ajudar a pessoa que tem uma conta na ByteBank a resolver esses problemas.