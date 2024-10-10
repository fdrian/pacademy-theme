# Instruções de Instalação do Tema da Pato Academy

Este documento fornece um guia passo a passo para instalar e aplicar o tema customizado da Pato Academy na sua instância do CTFd.

## Pré-requisitos

- Uma instância do CTFd instalada e em funcionamento.
- Acesso ao diretório de instalação do CTFd.

## Passo a Passo

### 1. Clone o Repositório

Primeiro, você precisa clonar este repositório em seu ambiente local. Execute o seguinte comando no terminal:

```bash
git clone https://github.com/fdrian/pacademy-theme.git
```

### 2. Navegue até o Diretório do Tema

Acesse o diretório do tema que você acabou de clonar:

```bash
cd pacademy-theme
```

### 3. Copie os Arquivos do Tema

Copie os arquivos do tema para o diretório de temas do CTFd. O caminho padrão é `CTFd/themes/`. Execute o seguinte comando:

```bash
cp -r * /caminho/para/seu/CTFd/themes/pato-academy/
```

### 4. Ative o Tema no CTFd

1. Acesse o painel de administração do CTFd.
2. Vá para **Settings** > **Theme** (`/admin/config#theme`).
3. Selecione o tema "Pato Academy" na lista de temas disponíveis.
4. Salve as alterações.

### 5. Verifique a Instalação

Após ativar o tema, acesse a página inicial do seu CTFd para verificar se o tema foi aplicado corretamente. Você deve ver a nova interface estilizada.

## Contribuições

Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Contato

Para mais informações ou suporte, entre em contato através das nossas redes sociais ou abra uma issue neste repositório.
