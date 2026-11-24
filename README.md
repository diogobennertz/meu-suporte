# Meu Suporte

Ferramenta de suporte para NF-e (Windows).

- **Corrigir status da nota**: consulta a nota (portal da NF-e ou webservice da SEFAZ com certificado) e gera o SQL para marcar como autorizada no sistema.
- **Conferir XML**: confere o XML de uma nota rejeitada e aponta o que está errado (assinatura, chave, datas, CNPJ/IE, CFOP, DIFAL, valores e totais), com explicação das rejeições mais comuns.
- **Buscar atualizações da Receita**: lista as Notas Técnicas novas do portal da NF-e.

## Instalar

Baixe o `MeuSuporte.exe` da [Release mais nova](../../releases/latest) e dê duplo clique. Ele se instala sozinho (sem administrador) e cria um atalho na Área de Trabalho.

## Atualizações

Ao abrir, o programa procura uma Release mais nova neste repositório e oferece para atualizar.

Para publicar uma versão nova: **Releases → Draft a new release**, tag `vX.Y.Z` (maior que a atual), escreva as novidades no texto e anexe o `MeuSuporte.exe`.
