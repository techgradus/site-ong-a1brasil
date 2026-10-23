# site-ong-a1brasil
Atualização do site institucional da ONG A1 Brasil em WordPress (tema HybridMag), com documentação do processo.

# Site Institucional ONG A1 Brasil

Projeto de extensão: atualização do site da **ONG A1 Brasil** em WordPress, seguindo um modelo visual (layout) definido para a organização.

- **Site no ar:** https://aumbrasil.com.br
- **Disciplina/Turma:** ADS 05 ° SEMESTRE Projeto de Extensão

## Integrantes

- Arthur Mendonca
- Beatriz Helena
- Bernardo Bacelar
- Elaine de Lima 
- Francisco Guilherme

## Sobre a ONG

A A1 Brasil é uma organização sem fins lucrativos, fundada em 2016 e sediada em Embu das Artes (SP). Promove inclusão social, cidadania e desenvolvimento sustentável por meio de projetos como o **Karatê para crianças** e a **Dança para a terceira idade**.

## Objetivo do projeto

Modernizar o site da ONG para que ele comunique melhor seu trabalho, com:

- Página inicial com destaque (hero) e chamada para apoio à ONG
- Seção **Nossos projetos**
- Seção **Nosso impacto** (indicadores)
- Seção **Sobre a A1 Brasil**
- **Notícias e atividades recentes**
- Menu principal: Início, A ONG, Projetos, Notícias e Contato
- Rodapé com endereço, contato, redes sociais e links úteis

## Tecnologias

| Item | Uso |
|------|-----|
| WordPress | Gerenciador de conteúdo (CMS) |
| Tema HybridMag | Tema base do site |
| Editor de blocos (Gutenberg) | Montagem das páginas |
| Elementor | [confirmar se foi utilizado] |
| HTML5, CSS3, JavaScript | Ajustes de layout e estilo |
| UpdraftPlus | Backup do site |
| GitHub | Portfólio e documentação |

## Processo realizado

1. **Backup de segurança:** instalação do plugin UpdraftPlus e backup antes de qualquer alteração ou atualização.
2. **Estudo do painel:** reconhecimento do painel do WordPress (posts, páginas, mídia, aparência, plugins).
3. **Identidade do site:** configuração do logo e das cores em Aparência → Personalizar.
4. **Páginas:** criação das páginas A ONG, Projetos, Notícias e Contato.
5. **Menu principal:** criação do menu e vínculo com a posição Primary Menu, na ordem definida pelo modelo.
6. **Cabeçalho:** substituição do botão padrão "Subscribe" por "Apoie a ONG".
7. **Página inicial:** montagem das seções do modelo com blocos.
8. **Notícias:** organização dos posts por categorias (Projetos, Eventos, Comunidade).
9. **Rodapé:** configuração de endereço, contato, redes sociais e links úteis.
10. **Revisão:** testes em computador, tablet e celular.

> Atualize esta lista marcando o que foi concluído e o que ficou pendente.

## Problemas encontrados e soluções

| Problema | Solução |
|----------|---------|
| Erro `googledrive_insufficient_permissions` ao conectar o UpdraftPlus ao Google Drive | Refazer a autorização marcando todas as permissões solicitadas pelo Google (ou fazer o backup no servidor e baixar o arquivo) |
| Menu de redes sociais confundido com o menu principal | Identificação das posições do tema (Primary, Top e Social Menu) e criação de um menu específico para o topo |
| Itens antigos no topo (HOME, Política de privacidade, SOBRE) | Menu principal criado e ligado à posição correta |

## Dados e privacidade (LGPD)

- Site institucional e público, sem cadastro de usuários e sem pagamento direto.
- Imagens de beneficiários (crianças e idosos) usadas apenas com autorização de imagem.
- Acesso administrativo restrito por login e senha.
- Backups e atualizações periódicas.
- Backups, senhas e arquivos de configuração **não** são publicados neste repositório.

## Uso de IA

Foi utilizado o **Claude (Anthropic)** como apoio de aprendizado e orientação no passo a passo do WordPress e na redação da documentação. A execução no painel, a escolha de conteúdo e imagens e a validação do resultado foram feitas pelo grupo.

## Estrutura do repositório

```
/
├── README.md          # esta documentação
├── prints/            # capturas de tela (modelo x resultado)
└── custom.css         # CSS adicional, se utilizado
```

## Status

Em andamento.
