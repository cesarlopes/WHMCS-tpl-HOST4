# WHMCS-tpl-HOST4

Personalização do template do [WHMCS](https://www.whmcs.com/) para a HOST4. O repositório reúne os arquivos do tema `host4`, baseados na estrutura de templates do WHMCS, para manter as customizações de apresentação sob controle de versão.

## Conteúdo do repositório

```text
templates/
├── host4/                  # Tema personalizado da HOST4
│   ├── css/, js/, img/      # Estilos, scripts e imagens do tema
│   ├── includes/, oauth/    # Partes reutilizáveis e telas OAuth
│   ├── store/               # Telas da loja e integrações de carrinho
│   └── *.tpl                # Páginas do cliente, faturas, suporte e domínio
├── six/                    # Arquivos do template SIX presentes no projeto
└── orderforms/             # Temas de formulários de pedido
```

Os arquivos `.tpl` são os templates do WHMCS. O tema `host4` contém também recursos estáticos próprios, como a imagem de logotipo em `templates/host4/img/logo.png`.

## Instalação

1. Faça backup do diretório de templates atualmente em uso na sua instalação do WHMCS e, se necessário, do banco de dados e das configurações relacionadas.
2. Revise as diferenças entre este repositório e os arquivos da sua instalação, principalmente se ela tiver personalizações locais.
3. Copie `templates/host4/` para `templates/host4/` na instalação do WHMCS, preservando a estrutura de diretórios. Não substitua outros temas sem antes revisar as diferenças.
4. Configure a instalação para usar o diretório de tema `host4` para a área do cliente, conforme a configuração disponível na sua versão do WHMCS.
5. Caso utilize um formulário de pedido deste repositório, copie somente o diretório correspondente em `templates/orderforms/` e selecione-o na configuração de pedidos do WHMCS.

## Antes de publicar alterações

- Teste primeiro em ambiente de homologação; confira fluxos de login, cadastro, carrinho, domínio, faturas e chamados que sejam usados pela sua operação.
- Mantenha um backup que permita restaurar rapidamente a versão anterior caso uma alteração de template cause comportamento inesperado.
- Não há uma matriz de compatibilidade ou uma versão de WHMCS declarada neste repositório. Valide o tema na versão da sua instalação antes de colocá-lo em produção.

## HOST4

Este projeto concentra a personalização visual do WHMCS utilizada pela HOST4. Para alterações, envie uma proposta que descreva a tela afetada e inclua validação em ambiente de homologação.

## Uso e licença

O repositório não contém um arquivo de licença. Antes de reutilizar ou redistribuir seus arquivos, confirme as permissões aplicáveis com os responsáveis pelo projeto e observe as licenças dos componentes de terceiros incluídos.
