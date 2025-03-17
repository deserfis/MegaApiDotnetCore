Crie uma documentação em markdown completa com design atraente com base nas características do projeto abaixo. A documentação deve ser clara, bem estruturada e visualmente agradável, seguindo as regras e limitações descritas a seguir.

Contexto:
Esse projeto é uma API feita em Python e Flask, utilizando Machine Learning para classificar os tipos de personalidade MBTI (Myers-Briggs Type Indicator). O objetivo principal é ser uma ferramenta que fornece respostas no formato JSON com o tipo de personalidade MBTI, baseado nas respostas do usuário a um conjunto de perguntas.

Formato de resposta esperado:

json
Copiar
Editar
{ 
  "Id": 1,
  "Code": "INTJ-99",
  "Name": "GoodName",
  "Age": 10,
  "PersonalityType": "INTJ",
  "Description": "The Architect – Known for strategic thinking and long-term planning.",
  "Picture": "https://example.com/johndoe.png"
}
Especificações do Projeto:
Versão: 1.0.0
Linguagens e Pacotes Utilizados:
Python 3.8+
Flask 2.0
scikit-learn 0.24.2 (para Machine Learning)
Pandas 1.2.3 (para manipulação de dados)
NumPy 1.20.1 (para cálculo numérico)
Regras e Limitações para a Criação do Arquivo Markdown:
Estruturação Lógica e Visual:

A documentação deve ser bem organizada com seções e subseções claras. Utilize títulos (com #, ##, ### etc.) para organizar os tópicos.
Não deve ser sobrecarregada de texto. Deve ter parágrafos curtos, bullets, listas numeradas e exemplos sempre que necessário.
Utilize blocos de código (com três crases, ```) para formatar os exemplos de código e JSON.
O design visual deve ser simples, mas agradável. Utilize negrito e itálico para destacar palavras-chave. Evite excessos de cores ou fontes que dificultem a leitura.
Utilização de Tabelas:

Quando listar dependências, use tabelas para organizar pacotes, versões e links para suas documentações oficiais. Exemplo de tabela:
markdown
Copiar
Editar
| Pacote       | Versão  | Link                                      |
|--------------|---------|-------------------------------------------|
| Flask        | 2.0     | [Flask](https://flask.palletsprojects.com/) |
| scikit-learn | 0.24.2  | [scikit-learn](https://scikit-learn.org/)  |
As tabelas devem ser simples, com 3 a 4 colunas no máximo.
Descrição do Projeto:

A seção de contexto e especificações do projeto deve ser clara e concisa. Ela precisa detalhar o propósito do projeto sem ser repetitiva.
Exemplos de inputs e outputs (JSON) devem ser fornecidos de maneira prática, com dados fictícios, para ilustrar como a API deve responder.
Regras de Estilo para o Texto:

Evite jargões técnicos excessivos e sempre que necessário, forneça explicações simples para termos mais complexos.
Seja direto e objetivo, sem prolixidade. O tom deve ser profissional, mas amigável.
Instruções ou comandos devem ser destacados em negrito (ex: Execute o comando), enquanto referências a arquivos ou URLs podem ser destacadas em itálico (ex: requirements.txt).
O uso de listas numeradas ou com bullet points deve ser priorizado para organização de tópicos.
Exemplos de JSON e Código:

Sempre que for necessário demonstrar exemplos de respostas da API, forneça-os de forma limpa, com indentação correta.
Os exemplos devem ser sempre realistas mas não precisam ser dados reais, apenas fictícios.
Referências e Links:

Quando mencionar qualquer dependência ou ferramenta externa, sempre forneça um link direto para a documentação oficial, preferencialmente em formato de hyperlink. Por exemplo, ao citar o pacote Flask: Flask.
Seja consistente com a forma de referenciar links ao longo do documento.
Detalhamento de Regras e Limitações (no contexto do arquivo):

A seção de regras e limitações deve detalhar as especificações de como a documentação deve ser seguida. Use bullet points para listar as regras que o modelo precisa seguir ao gerar a documentação em markdown.
Por exemplo, regras como: "A documentação não pode ultrapassar 500 palavras" ou "Deve incluir uma seção de licença no final".
Seção de Licença e Autores:

No final da documentação, deve ser incluída uma seção de licença, informando a licença sob a qual o projeto está sendo distribuído (por exemplo, MIT).
Incluir também uma seção com os autores do projeto ou colaboradores, se aplicável.
Design Responsivo e Acessível:

A documentação não precisa ser projetada como um site, mas deve ser organizada de forma que seja fácil de ler em qualquer editor de markdown, com boa legibilidade.
Evite o uso excessivo de imagens e elementos gráficos, focando no conteúdo técnico.
Tom e Abordagem da Documentação:

O tom deve ser amigável, encorajador e empático. A documentação deve inspirar confiança e tornar o projeto acessível para todos os níveis de desenvolvedores ou interessados.
Ao descrever funcionalidades ou como instalar o projeto, deve-se usar um tom orientador (ex: "Se você quiser começar, siga os passos abaixo...").
Instruções Finais:
A IA deve gerar um arquivo markdown que seja profissional, organizado e visualmente atraente.
O conteúdo deve ser claro e com instruções fáceis de seguir, com foco na clareza, simplicidade e funcionalidade.
O arquivo deve ser gerado com foco na leitura fácil, com uma hierarquia de informações clara, e sem erros de sintaxe Markdown.