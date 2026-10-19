# Isekai Feudalism — ambiente paralelo de testes 11.1.1

**Origem:** backup `Isekai-Feudalism-11.1.1-Site-Pronto.zip` do Google Drive.
**Estado:** cópia de testes preparada, **não** é a Live 11.4.1 e **não contém** implementações 11.4.3.

## Como testar

1. Extraia o ZIP mantendo todos os arquivos na mesma estrutura.
2. Execute `python -m http.server 8080` na pasta do projeto.
3. Abra `http://localhost:8080` no navegador.
4. Faça uma campanha de testes separada, sem importar saves da versão Live.
5. Para hospedar de forma independente, envie todos os arquivos desta pasta à raiz de um repositório dedicado de testes no GitHub e ative GitHub Pages em `main / (root)`.

## Proteção da Live

- Não substituir o site `isekai-feudalism-alpha.stillbream1.chatgpt.site`.
- Não confundir o código 11.1.1 com o mais recente 11.4.1.
- O armazenamento local pode compartilhar chaves se publicado no mesmo domínio: mantenha um domínio de testes independente.
- Não mover `index.html`, `js/`, `assets/`, `styles.css`, `v11.css`.

## Fluxo sugerido

Alterar somente em testes -> testar -> corrigir -> aprovar -> publicar. Ler `parâmetros de atuação 1.md` antes de cada etapa quando disponível na pasta de documentação do projeto.
