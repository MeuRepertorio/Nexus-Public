# Nexus — site público da administradora (TCC 2026)

Este repositório contém somente arquivos destinados à **divulgação acadêmica**. O repositório original e seus documentos de equipe permanecem privados.

## Como acessar
- **Site institucional:** `index.html`, publicado pela URL principal do GitHub Pages.
- **Apresentação da banca:** `banca/index.html`, no endereço `/banca/`.
- **Versão de consulta do Workspace para o professor:** `professor/index.html`, no endereço `/professor/`. É uma cópia **sem documentos internos**.

> **Atenção:** a rota `/professor/` é pública como qualquer outro caminho no GitHub Pages. Ela serve para facilitar o acesso pelo navegador, não para limitar o acesso apenas ao professor. Para privacidade verdadeira, usar autenticação por e-mail num serviço próprio. Não envie documentos internos para cá.

## Publicar com GitHub Pages
1. Abra **Settings → Pages** deste repositório.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione **main** e **/(root)**, e salve.
4. Aguarde o GitHub confirmar a publicação e teste a URL exibida.

Endereço normalmente esperado: `https://meurepertorio.github.io/Nexus-Public/`, sujeito à confirmação no GitHub Pages.

### Arquivos e escopo
```text
/
├── index.html          Site institucional
├── assets/             Estilos, JavaScript e ícone
├── banca/index.html    Apresentação online
├── professor/          Demonstração do Workspace sem anexos internos
├── robots.txt          Pedido de não indexar a versão docente
└── README.md           Este guia
```

A Nexus é um projeto acadêmico hipotético. Os valores de custo, parceiros e metas são **simulações**, não operações ou contratos efetivos. Ao atualizar arquivos na branch `main`, o Pages republica o site no mesmo endereço, desde que a configuração continue válida.
