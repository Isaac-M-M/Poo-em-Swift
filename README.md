# Classes e Objetos Swift com Pokémon  

Este repositório contém exemplos práticos sobre **Programação Orientada a Objetos (POO) em Swift**, utilizando a temática de **Pokémon** para ilustrar conceitos como **classes, objetos, métodos e inicializadores**.  

## 📌 Conteúdo  

- Introdução à **Programação Orientada a Objetos** em Swift  
- Definição de **Classes e Objetos**  
- Uso de **propriedades** e **métodos**  
- Criando e manipulando **instâncias**  
- Implementação de **métodos dentro da classe**  
- Uso de **inicializadores (`init`)**  

## 🏗 Criando uma Classe `Pokemon`  

swift
class Pokemon {
    var nome: String
    var tipo: String
    var hp: Int

    // Inicializador personalizado
    init(nome: String, tipo: String, hp: Int) {
        self.nome = nome
        self.tipo = tipo
        self.hp = hp
    }

    // Método para exibir informações do Pokémon
    func exibirInfo() {
        print("Nome: \(nome), Tipo: \(tipo), HP: \(hp)")
    }
}

// Criando um objeto da classe Pokemon
let pikachu = Pokemon(nome: "Pikachu", tipo: "Elétrico", hp: 200)
pikachu.exibirInfo()
🛡 Criando um Método para Ataque
swift
Copiar
Editar
class Pokemon {
    var nome: String
    var tipo: String
    var hp: Int

    init(nome: String, tipo: String, hp: Int) {
        self.nome = nome
        self.tipo = tipo
        self.hp = hp
    }

    // Método para atacar outro Pokémon
    func atacar(alvo: Pokemon) {
        print("\(nome) atacou \(alvo.nome) com um golpe do tipo \(tipo)!")
    }
}

// Criando dois Pokémon
let charmander = Pokemon(nome: "Charmander", tipo: "Fogo", hp: 180)
let squirtle = Pokemon(nome: "Squirtle", tipo: "Água", hp: 190)

// Simulando um ataque
charmander.atacar(alvo: squirtle)
🚀 Como Executar
Instale o Xcode ou use um Playground Swift.
Copie e cole o código no seu ambiente de desenvolvimento.
Execute e veja a mágica acontecer!
🔗 Referências
Documentação Oficial do Swift
Programação Orientada a Objetos em Swift

📌 Criado por: Isaac Mesquita Moreira
RGM 38211521
