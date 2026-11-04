# Meu Controle Financeiro

Controle financeiro para a família, que roda **no seu próprio computador**. Seus dados ficam só com você: nada vai para a internet nem para servidores de terceiros.

- Contas, cartões de crédito, faturas e compras parceladas
- Contas a pagar, recorrências (salário, aluguel, assinaturas) e calendário
- Painel, relatórios, gráficos e exportação para Excel
- Previsão do saldo, simulador de compras e metas
- Uso no celular (iPhone e Android), inclusive sem internet
- Cada pessoa da família com login próprio

## ⬇️ Baixar

**[Baixar o instalador para Windows](https://github.com/zSalvatorez/meu-controle-financeiro-download/releases/latest)**

Na página que abrir, clique em **Meu-Controle-Financeiro-Instalador-….exe**. Você não precisa de conta no GitHub.

Requisitos: Windows 10 ou 11, 64 bits.

---

## 1. Instalar no computador

1. Dê dois cliques no arquivo baixado.
2. O Windows pode mostrar **"O Windows protegeu o computador"**. Isso acontece com programas que não são de uma grande empresa. Clique em **Mais informações** e depois em **Executar assim mesmo**.
3. A instalação é automática e leva alguns segundos. No fim, o app abre no navegador.
4. Crie a conta de **administrador da família**: seu nome, e-mail e uma senha. O e-mail é só o seu login; o app não manda e-mails.

O programa vem **vazio**: você cadastra as contas, os cartões e os lançamentos da sua família. Ele fica rodando **perto do relógio** (ícone verde) e abre sozinho quando o computador liga.

- **Para abrir:** clique no ícone verde perto do relógio ou use o atalho **Meu Controle Financeiro** na área de trabalho.
- **Menu do ícone (botão direito):** conectar o celular, fazer backup, abrir a pasta dos dados, ligar ou desligar "Abrir junto com o Windows" e sair.

## 2. Usar no celular (opcional)

O celular acessa o app que está no seu computador, em casa ou na rua, pelo **Tailscale**. Ele é gratuito e cria uma ligação segura entre os seus aparelhos.

1. No computador, clique com o botão direito no ícone verde e escolha **Conectar o celular…**
2. Siga os passos da janela:
   - **Instale o Tailscale** no computador.
   - **Entre numa conta** do Tailscale (Google, Microsoft ou Apple).
   - Clique em **Ativar**. Na primeira vez, o Tailscale pode pedir para liberar o HTTPS: abra o link, confirme e clique em **Ativar** de novo.
3. No celular:
   - Instale o app **Tailscale** e entre na **mesma conta**.
   - Aponte a câmera para o **QR code** que aparece no computador.
   - Para virar um app na tela: no **iPhone**, toque em **Compartilhar → Adicionar à Tela de Início**; no **Android**, **menu → Instalar app**.

Para o celular funcionar, o computador precisa estar **ligado** e com o programa aberto. Sem conexão, o celular continua mostrando os últimos dados e guarda os lançamentos novos para enviar depois.

## 3. A família

- **Para adicionar alguém:** no app, vá em **Configurações → Família → Convidar pessoa**. A pessoa cria a própria conta com o código, e **cada um vê só as próprias finanças**.
- **No celular:** a pessoa precisa estar na mesma conta Tailscale. O jeito mais simples é usar o mesmo login do Tailscale em todos os celulares da casa.

## 4. Seus dados

- Os dados ficam em `%APPDATA%\MeuControleFinanceiro`, só no seu computador.
- O app faz **backup automático** todo dia e guarda os últimos 14.
- Em **Configurações → Seus dados → Exportar todos os dados**, você gera um arquivo com tudo, para guardar num pen drive ou na nuvem. Esse arquivo tem suas informações financeiras: **não envie para ninguém**.
- **Desinstalar** o programa não apaga os dados. Ao reinstalar, eles voltam.
- **Esqueceu a senha?** Outro administrador da família pode gerar uma senha temporária em **Configurações → Família**.

## 5. Versões novas

Volte a esta página e baixe o instalador mais recente. É só instalar por cima: os dados continuam.
