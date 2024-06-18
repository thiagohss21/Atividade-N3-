# Atividade-N3
Atividade N3 - Ciclo da Vida da Activity
Aluno: Thiago Henrique Souza e Silva
4º Período - Noite - Faculdade Nova Roma

Um breve resumo do que se trata o ciclo da vida de uma Activity, que trás a medida que o usuário navega no aplicativo, sai dele e retorna a ele, as instâncias do Activity no aplicativo transitam entre diferentes estaods no ciclo da vida, ou seja, a classe Activity fornece vários callbacks(o que é um callback -> é um conceito fundamental na programação que descreve a capacidade de uma função chamar a outra função como argumento), em termos simples, é uma função que é passada como paramêtro para outra função e é executada quando um determinado evento ocorre, ou seja, ele permite que atividade saiba quando um estado muda ou que o sistema está criando, interrompendo ou retomando uma atividade ou destruindo o processo em que ela está localizada.

Dentro dos métodos de callbacks do ciclo da vida, podemos declarar como atividade de se comportar quando o usuário sai e retorna dela. Um exemplo disso é se estiver sendo criado um play de streaming de vídeo, poderar pausar o vídeo e encerrar as conexões de rede quando o usuário alternar para outro app. Quando o usuário retornar, poderá se reconectar à rede e permitir que ele retome o vídeo do mesmo local. Nesse sentido, os callbacks são utilizados na programação em páginas da web, em manipulação de arquivos, requisições assícronas e também nas animações e transições.

Nestes contexto, uma boa implementação dos callbacks do ciclo da vida pode ajudar se app a evitar os seguintes pontos:

1. Falhas se o usuário receber uma chamada telefônica ou mudar para outro aplicativo enquanto estiver usando seu aparelho;
2. Consumo de recursos importantes do sistema quando o usuário não estiver usando ativamente o aplicativo; e
3. Falhas ou perda do progresso do usuário quando a orientação da tela mudar entre paisagem e retrato.

Em relação ao exposto acima, para navegar por transições entre os estágios do ciclo da vida da atividade, a class Activity fornece um conjunto principal de seis callbacks: 

1. onCreat();
2. onStart();
3. onResume();
4. onPause();
5. onStop();e
6. onDestroy();

O sistema invoca cada um desses callbacks à medida que atividade entra em um novo estado.
O layout abaixo demonstra a representação visual desse paradigma.

layout activity - ciclo da vida.png





