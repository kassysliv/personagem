# personagem
Conforme solicitado, melhorei o código original para deixá-lo mais completo, interativo e alinhado com Programação Orientada a Objetos. Criei a classe Heroi, herdando de Personagem, com métodos próprios como atacar(), usar_pocao(), salvar_refem() e dialogar(), além de um histórico para registrar as ações durante a batalha.

Adicionei um dicionário de itens na classe Heroi (espada, poção e escudo), usados nos métodos de ataque e cura. Na classe Vilao, modifiquei o método ataque() para variar o dano conforme o nível de maldade (Baixa, Média ou Alta) e com chance de ataque crítico (20%), tornando as batalhas mais dinâmicas.

No main(), implementei um menu interativo com ações de atacar, usar poção, salvar refém e fugir, além de um diálogo inicial entre herói e vilão para dar um toque narrativo. A batalha ocorre em um laço while que verifica a vida dos personagens, e as ações do usuário são registradas no histórico.

Também cuidei para evitar erros, usando max() para não deixar a vida negativa e validando as opções do usuário. Comentei os métodos para explicar as mudanças e organizei o código para facilitar manutenção e futuras melhorias.
