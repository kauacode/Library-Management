## Biblioteca - Sistema de Empréstimos de Livros

Este projeto em Java foi desenvolvido para aplicar conceitos fundamentais da linguagem, como herança, polimorfismo, estruturas de repetição e manipulação de datas. O sistema facilita a gestão de uma biblioteca, oferecendo funcionalidades para listar e realizar empréstimos de livros.

## Funcionalidades Principais

Consulta de Livros Disponíveis: Lista todos os livros que estão aptos para empréstimo. <br>
Registro de Empréstimos: Permite que um usuário selecione um livro disponível e registre um empréstimo, atualizando o status do livro.

## Estrutura do Sistema

O sistema é composto pelas seguintes classes principais:

Livro: Armazena informações dos livros, incluindo id, título, autor, status de disponibilidade, data de cadastro e data de atualização. <br>
Autor: Representa o autor dos livros, com atributos como id, nome e data de nascimento. <br>
Emprestimo: Gerencia os detalhes dos empréstimos, como o livro emprestado, o nome do usuário, e as datas de empréstimo e devolução. <br>
Biblioteca: Realiza a gestão da coleção de livros, autores e registros de empréstimos.

## Requisitos do Projeto
Java Development Kit (JDK) 8 ou versão superior. <br>
Ambiente de Desenvolvimento (IDE) de sua preferência, como Eclipse, IntelliJ IDEA, ou NetBeans.

## Como Executar o Sistema
Inicie o programa: Ao abrir o sistema, será perguntado se você deseja visualizar os livros disponíveis para empréstimo. <br>
Escolha o livro: Selecione um dos livros disponíveis para prosseguir com o empréstimo. <br>
Registre o Empréstimo: Após escolher o livro, registre o empréstimo com o nome do usuário, e o sistema marcará o livro como indisponível até a devolução.
