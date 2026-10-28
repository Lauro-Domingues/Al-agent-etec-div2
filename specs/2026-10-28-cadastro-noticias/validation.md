# Validação do recurso

## Critérios de aceitação
1. A área administrativa exige autenticação antes de permitir acesso.
2. O formulário aceita criação de notícias com campos obrigatórios.
3. As notícias são persistidas corretamente em SQLite.
4. A notícia publicada aparece na página inicial do site.
5. O usuário consegue editar e excluir registros sem erros.

## Verificações esperadas
- Validar campos vazios e mensagens de erro.
- Confirmar que usuários não autenticados não acessam o painel.
- Testar visualização em desktop e mobile.
- Verificar a apresentação do conteúdo em leitura clara.

## Condição para merge
A implementação pode ser mergeada quando:
- o fluxo de login e publicação funcionar sem falhas;
- a página inicial exibe as notícias corretamente;
- o caso de erro de autenticação e formulário estiver coberto;
- a interface estiver responsiva e consistente com o visual institucional.
