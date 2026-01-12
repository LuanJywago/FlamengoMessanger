# FlamengoMessanger

Sistema de envio de email automatizado e automático

Este sistema conta com a tecnologia em Python para automação e, principalmente, da biblioteca smtplib (responsável por manter contato e envio de emails através da conexão estabelecida em código.

**PASSOS PARA SEGUIR ANTES DE TESTAR E FUNCIONAR:**

**1. Crie sua senha de aplicativo**
  Para fazer o sistema funcionar corretamente via código, você precisará de uma senha de aplicativo, não sendo permitido utilizar sua senha comum de login. Isso se torna necessário porque o Google e a Microsoft bloqueiam acessos de aplicativos menos seguros por padrão (padrão de segurança).

   **1.1. Como criar sua senha de aplicativo:**
     **1.1.1 Google (Gmail)**
1. ​Importante: Você precisa ter a "Verificação em duas etapas" ativada na sua conta Google para que esta opção apareça.
​2. Acesse sua Conta do Google.
​3. No menu lateral, clique em Segurança.
​4. Em "Como você faz login no Google", clique em Verificação em duas etapas.
​5. Role até o final da página e clique em Senhas de app.
​6. Dê um nome ao app (ex: "FlamengoMessenger") e clique em Criar.
7. ​O Google vai gerar uma senha de 16 caracteres em um quadrado amarelo.
​8. Copie e salve agora! Você não conseguirá vê-la novamente.

>[TIP!]
>**DICA:** No seu código (dentro do seu .env), use essa senha de 16 dígitos sem os espaços.
   
  **1.1.​2. Hotmail / Outlook (Microsoft)**
1. ​Assim como no Google, a verificação em duas etapas deve estar ativa.
​2. Acesse a página de Segurança da conta Microsoft.
​3. Clique em Opções de segurança avançadas.
​4. Procure a seção Senhas de aplicativos (geralmente fica no meio/fim da página).
​5. Clique em Criar uma nova senha de aplicativo.
​6. A senha será gerada na tela. Copie-a e clique em "Concluído".

**2. Faça o git clone deste repositório**
  Para fazer o git clone é fácil, utilize os comandos a baixo:
  git clone [https://github.com/LuanJywago/FlamengoMessanger.git](https://github.com/LuanJywago/FlamengoMessanger.git)
  cd ./FlamengoMessanger

  Pronto para o uso.


**3. Configurações importantes**
É extremamente importante proteger seu email (apenas por via das dúvidas mesmo) e sua senha (mais importante), então, crie os seguintes arquivos abaixo:

  **3.1 .env**
    Este arquivo cria uma espécie de ambiente virtual para definir caracteristicas padrões dentro do código, assim como "my_email" e "password". Portanto, considere utilizá-lo para o próximo arquivo.
    Exemplo:
    <img width="324" height="113" alt="image" src="https://github.com/user-attachments/assets/911fc28a-1dd0-4b28-89ca-5158f6aa0367" />

  **3.2 .gitignore**
    Este arquivo, quando upado para o github, ele basicamente estabelece uma comunicação com a plataforma e fala **"Este arquico NÃO DEVE PASSAR (.env)"** por conter senhas, dados, características críticas.
    Um exemplo disso:
    <img width="211" height="125" alt="image" src="https://github.com/user-attachments/assets/bec4dd6c-916b-4c2b-90f4-771cc196a202" />
    Portanto, proteja-os

**4. Certifique-se das datas**
O arquivo "datas.csv" ele contém todas as datas, adversários e (alguns) campeonatos atualizados e outros desatualizados.
Caso isso o incomode, apenas altere os dados dentro deste arquivo.
>[CAUTION"]
>Não coloque **ESPAÇO** depois das virgulas dentro deste arquivo. O arquivo csv (Comma-Separated Values ou Valores Separados por Vírgula) não contém espaço.


**5. Configurando no PythonAnyware**
Como o arquivo .env não vai para o GitHub (graças ao passo 3), quando você clonar o código no PythonAnywhere, ele não terá as senhas. Você precisa criá-las lá manualmente uma única vez.
​Existem duas formas de fazer isso no PythonAnywhere. A mais simples para este caso (script de automação) é criar o arquivo .env lá dentro.

  5.1. Entre no painel do PythonAnyware e vá em Files (PythonAnyware -> Files).
  5.2. Navegue até a pasta de onde você salvou o projeto (main.py).
  5.3. Crie um novo arquivo chamado .env.
  5.4. Cole o conteúdo com suas senhas (igual ao que fizeste no pc).
  5.5. Salve.

>[IMPORTANT!]
>No pythonAnyware, você também precisará instalar a biblioteca python dotenv. Se ainda não tiver feito:
>1. Abra um bash;
>2. Digite: pip3.10 install python-dotenv --user (baixa na versão 3.10 do python, se for diferente, mude para a versão que você está utilizando)

Do mais, apenas botar para rodar e seja feliz com os emails chegando no dia dos jogos !

Fico a disposição para demais dúvidas.
