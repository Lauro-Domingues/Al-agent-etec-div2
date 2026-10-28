# Requisitos do recurso

## Escopo
Este recurso contempla o cadastro, listagem, edição e exclusão de notícias no site institucional da escola técnica.

## Decisão
A funcionalidade deve ser administrada por uma área restrita do sistema, permitindo que a equipe publique notícias sem expor ferramentas internas ao público.

## Contexto
A missão do projeto exige clareza, confiabilidade e comunicação institucional. O site precisa divulgar notícias relevantes para a comunidade escolar. A stack escolhida usa Next.js com TypeScript e SQLite como solução leve para o MVP.

## Inclusões
- login administrativo
- formulário com título, resumo e conteúdo
- persistência em SQLite
- listagem de notícias
- publicação na página inicial

## Exclusões
- comentários públicos
- múltiplos perfis administrativos complexos
- sistema de mídia avançado
- integrações externas no escopo inicial

## Observações
O recurso prioriza simplicidade de operação, segurança de acesso e compatibilidade com dispositivos móveis.
