# 🔴⚫ FlamengoMessenger

> Sistema automatizado de envio de e-mails para notificações de jogos do Flamengo.

Este projeto utiliza *Python* e a biblioteca nativa smtplib para monitorar datas de jogos e enviar notificações automáticas via e-mail, garantindo que você nunca perca uma partida do Mengão.

---

## 📋 Pré-requisitos

Antes de começar, você precisará de:
* *Python 3.10* ou superior.
* Uma conta de e-mail (Gmail ou Outlook/Hotmail) com *autenticação de dois fatores (2FA)* ativada.
* Uma *Senha de Aplicativo* gerada (instruções abaixo).

---

## 🔐 Configuração da Senha de Aplicativo

Para que o script acesse seu e-mail, *não utilize sua senha pessoal*. É obrigatório gerar uma senha específica para aplicativos devido às políticas de segurança do Google e Microsoft.

### 1. Google (Gmail)
1.  Acesse sua [Conta do Google](https://myaccount.google.com/).
2.  No menu lateral, clique em *Segurança*.
3.  Verifique se a *Verificação em duas etapas* está ativa (se não, ative-a).
4.  No campo de busca da página, digite *"Senhas de app"* e clique na opção.
5.  Dê um nome ao app (ex: FlamengoBot) e clique em *Criar*.
6.  *Copie a senha de 16 caracteres* gerada imediatamente. Você não poderá vê-la novamente.

### 2. Microsoft (Outlook/Hotmail)
1.  Acesse a página de [Segurança da Microsoft](https://account.microsoft.com/security).
2.  Vá em *Opções de segurança avançadas*.
3.  Role até a seção *Senhas de aplicativos* e clique em "Criar uma nova senha de aplicativo".
4.  Copie a senha gerada.

---

## 🚀 Instalação e Uso Local

### 1. Clone o repositório
Abra seu terminal e execute:

```bash
git clone [https://github.com/LuanJywago/FlamengoMessanger.git](https://github.com/LuanJywago/FlamengoMessanger.git)
cd FlamengoMessanger

2. 2. Configure as Variáveis de Ambiente (.env)
​Por segurança, as senhas nunca devem ficar expostas no código.
​Crie um arquivo chamado .env na raiz do projeto.
​Adicione o seguinte conteúdo (substituindo pelos seus dados):

​<!-- end list -->


