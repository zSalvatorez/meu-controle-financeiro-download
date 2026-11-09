# Meu Controle Financeiro

Controle financeiro para a família, no computador e no celular.

- Contas, cartões de crédito, faturas e compras parceladas
- Contas a pagar, recorrências (salário, aluguel, assinaturas) e calendário
- Painel, relatórios, gráficos e exportação para Excel
- Previsão do saldo, simulador de compras e metas
- Uso no celular (iPhone e Android), como um app na tela inicial
- Cada pessoa da família com login próprio

## ⬇️ Baixar

**[Baixar o instalador para Windows](https://github.com/zSalvatorez/meu-controle-financeiro-download/releases/latest)**

Na página que abrir, clique em **Meu-Controle-Financeiro-Instalador-….exe**. Você não precisa de conta no GitHub.

Requisitos: Windows 10 ou 11, 64 bits.

---

## 1. Instalar

1. Dê dois cliques no arquivo baixado.
2. O Windows pode mostrar **"O Windows protegeu o computador"**. Isso acontece com programas que não são de uma grande empresa. Clique em **Mais informações** e depois em **Executar assim mesmo**.
3. A instalação é automática e leva alguns segundos.

Na primeira vez, o programa pergunta **como você quer usar**:

| | **Na nuvem** (recomendado) | **Só neste PC** |
|---|---|---|
| Celular | Funciona **com o computador desligado** | Só com o computador ligado |
| Onde ficam os dados | Numa conta grátis da Cloudflare **só sua** | Neste computador |
| Custo | Grátis, sem cartão de crédito | Grátis |

Dá para mudar depois.

## 2. Na nuvem (recomendado)

O programa guia você em 3 passos, que levam uns 5 minutos:

1. **Criar uma conta grátis na Cloudflare.** É a empresa que vai guardar o app e os dados, numa conta **só sua**: ninguém mais tem acesso, nem quem fez o programa. Não precisa de cartão.
2. **Criar a chave de acesso.** O programa abre a página da Cloudflare já preenchida:
   - desça até o fim e clique em **Continue to summary**;
   - clique em **Create Token**;
   - clique em **Copy** e cole no programa.

   A chave só serve para publicar o app na sua conta e fica guardada criptografada no seu computador.
3. **Publicar.** O programa coloca o app na sua conta e mostra o **endereço** e um **QR code** para o celular.

Depois, crie a conta de **administrador da família** no app: seu nome, e-mail e uma senha. A primeira conta só pode ser criada pelo programa do computador. Assim, ninguém que descubra o endereço consegue se cadastrar antes de você.

**Já usava a versão que fica só no computador?** Na primeira abertura depois de atualizar, o programa oferece levar tudo para a nuvem. Ele confere que todos os dados chegaram iguais, e o banco do computador continua guardado como cópia. A opção também fica no menu do ícone perto do relógio: **Usar na nuvem…**

**No celular:** aponte a câmera para o QR code e abra o link. Para virar um app na tela:
- **iPhone:** toque em **Compartilhar → Adicionar à Tela de Início**;
- **Android:** toque em **menu → Instalar app**.

O programa do computador continua perto do relógio:
- abre o app numa janela;
- faz uma **cópia de segurança diária** dos seus dados da nuvem;
- **atualiza o app na nuvem sozinho** quando você instala uma versão nova.

## 3. Só neste PC

O programa vem **vazio**: você cadastra as contas, os cartões e os lançamentos da sua família. Ele fica rodando **perto do relógio** (ícone verde) e abre sozinho quando o computador liga.

Para usar no celular, clique com o botão direito no ícone verde e escolha **Conectar o celular…**. O celular acessa o computador pelo **Tailscale**, que é gratuito. Siga os passos da janela. Nesse modo, o celular só funciona com o computador **ligado**.

## 4. A família

**Para adicionar alguém:** no app, vá em **Configurações → Família → Convidar pessoa**. A pessoa cria a própria conta com o código, e **cada um vê só as próprias finanças**.

## 5. Seus dados

- **Na nuvem:**
  - os dados ficam na **sua** conta da Cloudflare;
  - o programa do computador guarda uma cópia por dia em `%APPDATA%\MeuControleFinanceiro\backups`;
  - a Cloudflare também guarda o histórico dos últimos 30 dias.
- **Só neste PC:** os dados ficam em `%APPDATA%\MeuControleFinanceiro`, com backup automático todo dia.
- Em **Configurações → Seus dados → Exportar todos os dados**, você gera um arquivo com tudo. Esse arquivo tem suas informações financeiras: **não envie para ninguém**.
- **Desinstalar** o programa não apaga os dados.
- **Esqueceu a senha?** Outro administrador da família pode gerar uma senha temporária em **Configurações → Família**.

## 6. Versões novas

Volte a esta página e baixe o instalador mais recente. É só instalar por cima: os dados continuam. No modo nuvem, o programa também atualiza o seu app na nuvem sozinho.
