<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Sistema de Gestão para a Farmácia Vida Saudável&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Ana Clara
* Dayô Araujo
* Enzo Viana


# Descrição do Projeto
*&lt;A Farmácia Vida Saudável tem crescido e, com isso, surgiu a necessidade de melhorar a organização do dia a dia. Hoje, tudo é feito manualmente, com anotações em cadernos e planilhas, o que pode causar erros e atrasos no atendimento.

Para resolver esse problema, o Sr. Boticário decidiu modernizar a farmácia com um sistema informatizado. Com a ajuda da MACK Solutions SW, esse sistema vai facilitar o controle de vendas, estoque e clientes, tornando o trabalho mais ágil e eficiente para todos.&gt;*

# Análise de Requisitos Funcionais e Não-Funcionais
*&lt;Requisitos Funcionais:
1. Cadastro de Medicamentos e Produtos
2. Cadastro de Clientes
3. Processo de Venda
4. Controle de Estoque
5. Relatórios Gerenciais
&gt;*

*&lt;Requisitos Não Funcionais:
1. Usabilidade
2. Desempenho
3. Segurança
4. Escalabilidade
5. Confiabilidade
6. Compatibilidade
&gt;*

# Diagrama de Atividades

graph TD
    A(Início) -->|Cliente chega à farmácia| B[Atendente pesquisa produto no sistema]
    B --> C{Produto disponível?}
    C -->|Sim| D[Registrar venda]
    D --> E[Associar venda ao CPF do cliente]
    E --> F[Atualizar estoque automaticamente]
    F --> G[Gerar cupom fiscal]
    G --> H[Cliente realiza pagamento]
    H --> I[Entregar produto ao cliente]
    I --> J[Fim]

    C -->|Não| K[Informar indisponibilidade]
    K --> J

    subgraph Gestão Administrativa
        L[Administrador acessa o sistema] --> M[Gerar relatórios de vendas e estoque]
    end


# Diagrama de Casos de Uso

*&lt;Diagrama para visualizar o comportamento dos atores&gt;*

# Descrição dos Casos de Uso

*&lt;Descrição do comportamento entre os atores/resquisitos&gt;*

# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
