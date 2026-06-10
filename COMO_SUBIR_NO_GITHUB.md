# Como subir o Black Void Universal no GitHub via terminal

Siga os passos abaixo exatamente nesta ordem.

---

## Passo 1: Criar o repositório no GitHub (pelo navegador)

1. Acesse: https://github.com/new
2. Nome do repositório: `black-void-universal` (recomendado)
3. Deixe como **Public**
4. **Não** marque "Add a README file" (porque já temos um)
5. **Não** adicione .gitignore ou license agora
6. Clique em **Create repository**

---

## Passo 2: Preparar no terminal (no seu computador)

Abra o terminal na pasta onde está o projeto.

```bash
# Entre na pasta do projeto (se ainda não estiver)
cd caminho/para/black-void-universal

# Inicialize o git
git init

# Adicione todos os arquivos
git add .

# Faça o primeiro commit
git commit -m "Primeira versão: Black Void Universal - Sistema de prompts acessíveis"

# Adicione o repositório remoto (troque SEU-USUARIO pelo seu usuário do GitHub)
git remote add origin https://github.com/SEU-USUARIO/black-void-universal.git

# Envie para o GitHub (branch principal)
git branch -M main
git push -u origin main
```

---

## Passo 3: Configurar o repositório no GitHub (após o push)

Depois que o push terminar, vá no navegador para o seu repositório e faça o seguinte:

### Descrição (Description)
Cole isso:

```
Transforme qualquer conteúdo em materiais de estudo ultra-acessíveis para TDAH, TEA, Dislexia, Discalculia, Ansiedade e todos os perfis. Funciona com qualquer IA usando só o link do GitHub.
```

### About (seção About)
Cole a versão completa que está no arquivo `DESCRICAO_REPOSITORIO.md` (seção 3).

### Topics (Tags)
Adicione estas tags:

```
acessibilidade
tdah
tea
dislexia
discalculia
educacao-inclusiva
neurodivergente
estudos
aprendizagem
ansiedade
prompt-engineering
materiais-didaticos
ia
chatgpt
claude
```

---

## Passo 4: Atualizar os links no README (importante!)

Depois de criar o repositório, edite o arquivo `README.md` e substitua todas as ocorrências de:

`SEU-USUARIO`

pelo seu nome de usuário real do GitHub.

Exemplo de onde aparece:
- Na seção "Como usar"
- No final do README

Você pode fazer isso com busca e replace.

---

## Dica extra

Se quiser deixar o repositório mais bonito, depois do primeiro push você pode:

1. Adicionar uma imagem de capa (banner) nas configurações do repositório
2. Criar uma pasta `images/` e colocar ícones ou exemplos
3. Adicionar o arquivo `DESCRICAO_REPOSITORIO.md` como referência interna

---

Pronto! Depois de rodar os comandos acima, seu repositório estará no ar e qualquer pessoa poderá usar só com o link.

Se der algum erro (ex: "remote origin already exists"), me avise que eu te passo o comando para corrigir.