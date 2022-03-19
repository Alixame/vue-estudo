# Estudo VUE.js


<h3 align="center"> Aula 01 </h3>

É Demonstrado um pouco de como funciona a sintaxe do Vue

    options = {
        el: "", // Definindo o Elemento Principal que Sera Trabalhado // # -> id // . -> class
        data: {}, // Definindo Variaveis
        methods: {} // Definindo Funções (metodos)
    }

    const vn = new Vue(options) <- OBS: Geralmente o elemento, variaveis, e metodos são declarados na propria instancia da classe, nesse exemplo estamos armazenando os dados numa variavel para melhor entendimento.

Está sintaxe deve ser definida dentro do script js e incorporada no seu site

    options = {
        el: "", // Definindo o Elemento Principal que Sera Trabalhado 
        data: {}, // Definindo Variaveis
        methods: {} // Definindo Funções (metodos)
    }

    const vn = new Vue(options) <- OBS: Geralmente o elemento, variaveis, e metodos são declarados na propria instancia da classe, nesse exemplo estamos armazenando os dados numa variavel para melhor entendimento.

Para definir o elemento principal que será trabalhado basta seguir a sintaxe:

    el: "#nome_do_elemento", // Utilize "#" quando for pegar o elemento pelo seu id //  Utilize "." quando for pegar o elemento pela class

É possivel  definir todos os tipos de variaveis , string, int, float, arrays, objetos seguindo está sintaxe:

    data: {
        nome da variavel: valor // Lembre-se que dependendo da varaivel deve ser envolvida por "" -> string, [] -> arrays  ou {} -> objetos, valores numeros basta colocar o valor em numeros sem envolver.
    },

<h3 align="center"> Aula 02 </h3>