# Hackathon Relâmpago: Caçadores de Fraudes

Contexto

Você e sua equipe acabam de ser contratados por um órgão de controle interno para uma missãocrítica: detectar irregularidades em compras públicas utilizando suas habilidades emprogramação Python. A reputação de vocês está em jogo. Em duas horas, devem entregar um protótipo funcional que analisa uma base de compras e gera um relatório de riscos automatizado. 

Equipes

• Times de até 3 participantes 
• Todos devem contribuir com o código (pares serão aleatórios caso o aluno não tenha equipe)

Dataset Oficial

Será fornecido em tempo real durante o hackathon.

Formato:

compras = [["servidor", "item", valor(float), "hora(HH:MM)"]]

Desafio

Construir uma aplicação em Python que, ao receber a lista de compras, consiga:
1. Detectar compras duplicadas
2. Listar valores acima do limite (R$1000)
3. Identificar compras fora do horário comercial (antes de 08:00 ou depois de 18:00)
4. Organizar as compras por servidor usando dicionários
5. Exibir relatório com severidade da infração
6. Usar funções para modularização
7. Usar list comprehensions sempre que possível

Regras Técnicas

• Todo o código deve ser escrito durante o evento
• Comentários no código são obrigatórios 
• As soluções devem rodar diretamente via terminal Python

Cronograma

00:00 - 00:10 | Apresentação do desafio e formação dos times

00:10 - 01:30 | Desenvolvimento (sem internet, apenas anotações pessoais)

01:30 - 01:45 | Testes finais e apresentação do relatório no terminal

01:45 - 02:00 | Avaliação das equipes e anúncio da equipe destaque

Entregáveis

1. Código Python funcional (hackathon.py)
2. Relatório gerado via terminal com: - Total de fraudes
- Listagem por tipo (duplicação, valor, horário)
- Nível de severidade
3. Explicação rápida da lógica usada (oral ou por comentário no código)
