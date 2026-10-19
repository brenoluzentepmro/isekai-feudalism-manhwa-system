# Parâmetros de atuação 1

Projeto: Isekai Feudalism
Versão do protocolo: 1.0 — 19/10/2026

## Aplicação obrigatória
Antes de planejar, implementar, testar ou publicar qualquer atualização, ler integralmente este arquivo e aplicar suas regras. Se o arquivo não estiver acessível, solicitar acesso e não afirmar que foi lido. O agente executor deve registrar no relatório que o leu.

## Ciclo de atualização
1. Ler este protocolo e a especificação da versão.
2. Inspecionar apenas os arquivos e dependências relevantes; identificar riscos e estimar complexidade (baixa/média/alta).
3. Criar backup/ponto de restauração e estabelecer critérios de aceite.
4. Implementar somente o escopo aprovado, com mudanças mínimas e reutilização de código.
5. Executar testes direcionados, de regressão e de persistência; corrigir bugs críticos antes de prosseguir.
6. Validar mobile e desktop quando afetados; verificar salvamentos existentes.
7. Antes de publicar, revisar diffs, testes, bugs pendentes e versão; publicar somente com validação e autorização.
8. Criar no Google Drive uma pasta com o nome da versão e exportar para ela a especificação, o relatório de testes e este protocolo (ou referência ao protocolo central). Confirmar que os arquivos foram enviados; não declarar publicação sem comprovação.

## Uso econômico dos recursos do GPT Plus
- O consumo de recursos deve ser suficiente para implementação, testes e correções, sem esgotar desnecessariamente os limites disponíveis.
- Planejamento indicativo do esforço: 60% implementação, 30% testes/correções, 10% reserva de segurança. Não são percentuais mensurados de créditos nem garantia de limites.
- Evitar reanálises do projeto inteiro, leituras redundantes, refatorações extensas e reescrita integral de arquivos quando patches bastarem.
- Priorizar testes essenciais e direcionados, mas nunca suprimir testes críticos para economizar.
- Se o esforço exceder a estimativa, parar novas funcionalidades, preservar estado estável e reportar pendências; dividir a entrega em nova subetapa.
- O agente não deve alegar conhecer o saldo de créditos do usuário sem fonte verificável.

## Controle de qualidade e publicação
- Nenhuma etapa avança com bug crítico ou regressão não resolvida.
- Nunca afirmar que executou teste, implementou código, exportou ou publicou sem evidência.
- Preservar compatibilidade dos salvamentos e não alterar mecânicas fora do escopo.
- Relatório conciso obrigatório: alterações/arquivos, testes executados e resultados, bugs corrigidos, pendências, impacto em saves/mobile/desktop, aprovação e situação de publicação.
- Separar os estados: planejado, implementado, testado, aprovado, publicado.
