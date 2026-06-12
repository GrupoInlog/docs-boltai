# Canais

**Caminho:** Administração → Canais

Canais são as contas e integrações externas por onde a plataforma envia e recebe mensagens. Cada tipo de canal tem seu próprio fluxo de conexão.

---

## WhatsApp (via Meta API)

Integração oficial com o WhatsApp Business Platform da Meta.

**Como conectar:**

1. Clique em **Conectar** no card do WhatsApp (Meta).
2. Autorize o acesso à sua conta Meta Business.
3. A plataforma detecta automaticamente o Número de Telefone e o ID da conta WABA.
4. Defina um **nome** para identificar esta conexão.
5. Configure o **controle de acesso**: selecione os usuários e/ou departamentos que poderão usar este canal.
6. Salve.

---

## WhatsApp (via Bolt)

Integração via provedor Bolt (UAZAPI ou AVISAAPI), utilizando o WhatsApp Web vinculado a um número de celular.

**Como conectar:**

1. Clique em **Conectar** no card do WhatsApp (Bolt).
2. Defina um **nome** para a conexão.
3. Um QR Code será exibido.
4. Abra o WhatsApp no celular, acesse **Dispositivos conectados** e escaneie o QR Code.
5. Após a leitura, a conexão é confirmada automaticamente.
6. Configure o **controle de acesso** (usuários e departamentos).
7. Salve.

---

## Instagram

Integração com o Instagram Direct (contas Business).

**Como conectar:**

1. Clique em **Conectar** no card do Instagram.
2. Você será redirecionado para a autorização via Meta/Facebook.
3. Autorize o acesso à conta Instagram Business desejada.
4. Ao retornar, defina um **nome** para a conexão.
5. Configure o **controle de acesso**.
6. Salve.

---

## Facebook Messenger

Integração com o Messenger de uma Página do Facebook.

**Como conectar:**

1. Clique em **Conectar** no card do Facebook Messenger.
2. Você será redirecionado para a autorização via Meta/Facebook.
3. Selecione a Página do Facebook que deseja integrar.
4. Ao retornar, defina um **nome** para a conexão.
5. Configure o **controle de acesso**.
6. Salve.

---

## Gmail

Integração com uma conta Gmail para envio e recebimento de e-mails.

**Como conectar:**

1. Clique em **Conectar** no card do Gmail.
2. Você será redirecionado para a tela de autorização do Google.
3. Selecione ou faça login com a conta Gmail desejada e autorize as permissões solicitadas.
4. Ao retornar, defina um **nome** para a conexão.
5. Configure o **controle de acesso**.
6. Salve.

---

## Outlook

Integração com uma conta Outlook/Office 365 para envio e recebimento de e-mails.

**Como conectar:**

1. Clique em **Conectar** no card do Outlook.
2. Você será redirecionado para a tela de autorização da Microsoft.
3. Faça login com a conta desejada e autorize o acesso.
4. Ao retornar, defina um **nome** para a conexão.
5. Configure o **controle de acesso**.
6. Salve.

---

## Gerenciar canais conectados

Para cada canal já conectado, as seguintes ações estão disponíveis:

| Ação | Descrição |
|---|---|
| **Editar** | Alterar nome da conexão ou controle de acesso |
| **Desativar** | Suspende a conexão sem excluí-la |
| **Reativar** | Reativa uma conexão previamente desativada |
| **Reconectar** | Disponível quando o token expirou (ícone ⚠️). Refaz a autenticação OAuth |

O número de contas conectadas e o número de conexões que precisam de atenção são exibidos em cada card de canal.

---

## Controle de acesso por canal

Ao criar ou editar qualquer canal, é possível restringir o acesso por:

- **Usuários específicos**: somente esses atendentes poderão enviar mensagens por este canal.
- **Departamentos específicos**: somente usuários dos departamentos selecionados terão acesso.

!!! info "Sem restrições"
    Se nenhuma restrição for configurada, todos os usuários ativos da plataforma terão acesso ao canal.
