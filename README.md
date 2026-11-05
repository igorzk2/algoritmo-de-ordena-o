# Sistema de Gerenciamento de Notas

Projeto de estudo desenvolvido com HTML, CSS e JavaScript para praticar cadastro, busca e ordenação de dados de alunos em uma interface web.

## Funcionalidades

- Exibição de três alunos de exemplo.
- Cadastro de alunos com nome, matrícula e notas de Matemática e Português.
- Busca por parte do nome ou da matrícula.
- Ordenação por nome, matrícula ou nota de cada disciplina.
- Escolha de ordem crescente ou decrescente.

## Tecnologias utilizadas

- HTML: estrutura da página.
- CSS: aparência da interface.
- JavaScript: cadastro, busca, ordenação e atualização da tabela.

O projeto utiliza recursos nativos do navegador, sem bibliotecas externas.

## Como executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/igorzk2/algoritmo-de-ordena-o.git
   ```

2. Abra a pasta baixada.
3. Entre na pasta `sistemas-notas.html`.
4. Abra o arquivo `index.html` em um navegador.

Também é possível baixar pelo GitHub em **Code → Download ZIP**, extrair o conteúdo e abrir o mesmo arquivo.

Não é necessário instalar dependências ou configurar um banco de dados.

## Como utilizar

1. Preencha o nome, a matrícula e as duas notas.
2. Clique em **Adicionar Aluno**.
3. Para buscar, escolha nome ou matrícula, digite o termo e clique em **Buscar**.
4. Para exibir todos novamente, faça uma busca com o campo vazio.
5. Para ordenar, selecione o critério e a direção e clique em **Aplicar**.

## Organização dos arquivos

- `sistemas-notas.html/index.html`: página com HTML, CSS e JavaScript.
- `README.md`: documentação do projeto.
- `LICENSE`: licença de software.

## Limitações atuais

- Os novos cadastros ficam apenas na memória e são perdidos ao recarregar a página.
- O botão **Relatório** é apenas visual e ainda não gera relatórios.
- Não há edição ou exclusão de alunos.
- Matrículas duplicadas não são bloqueadas.
- A validação de notas entre 0 e 10 precisa ser reforçada no JavaScript.
- A ordenação considera todos os alunos, mesmo após uma busca.

## Licença

Este projeto está disponibilizado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE).
