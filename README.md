# Desafio DEV - Escolha Seu Personagem

<div align="center">
  <img src="./src/imagens/hulk.png" alt="Tela de seleção de personagens" width="500"/>
</div>

## Descrição do Projeto

Este projeto é uma interface de seleção de personagens no estilo de jogos de luta, criado durante um curso dos irmãos **Dev em Dobro**. A aplicação permite aos jogadores escolher diferentes heróis e vilões da Marvel, atualizando dinamicamente a imagem e o nome do personagem principal selecionado. O projeto utiliza HTML, CSS e JavaScript para proporcionar uma experiência interativa e responsiva.

Essa versão enfatiza o **Dev em Dobro** de forma clara. Se precisar de mais ajustes, é só avisar!

## Funcionalidades

- **Interatividade com o Mouse**: Ao passar o mouse sobre os personagens, o personagem selecionado muda de aparência e seu nome aparece na área correspondente ao jogador.
- **Alteração Dinâmica de Conteúdo**: A imagem e o nome do personagem principal são alterados automaticamente quando o jogador seleciona um novo personagem.
- **Personagens Duplos**: Permite que dois jogadores escolham seus personagens independentemente.

## Tecnologias Utilizadas

- **HTML5**: Estrutura básica da aplicação.
- **CSS3**: Estilização e animações dos personagens e da interface, dividido em arquivos para variáveis, reset, fontes, animações, estilos e responsividade.
- **JavaScript**: Manipulação da DOM para implementar as funcionalidades dinâmicas, como a troca de personagens selecionados.

## Como Executar o Projeto

1. **Clone o Repositório**

   No terminal, execute:
   ```bash
   git clone https://github.com/seu-usuario/character-select.git
   ```

2. **Abra o Projeto no Navegador**

   Navegue até o diretório do projeto e abra o arquivo `index.html` no seu navegador para visualizar a interface de seleção de personagens.

## Exemplo de Uso

Ao abrir o projeto no navegador, o jogador verá uma lista de personagens da Marvel. Ao passar o mouse sobre qualquer personagem na lista, o personagem principal (Jogador 1) será atualizado automaticamente, refletindo a escolha. O Jogador 2 permanece fixo no personagem Ultron, conforme a lógica implementada.

## Personalização

Você pode adicionar mais personagens ao jogo ou alterar as imagens existentes:
- Adicione novas imagens na pasta `src/imagens`.
- Atualize o HTML e o JavaScript para incluir o novo personagem na seleção.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou fazer um fork do repositório e enviar pull requests.

1. Faça um fork do projeto.
2. Crie uma nova branch para sua feature (`git checkout -b feature/nome-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Envie para a branch (`git push origin feature/nome-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.
