## SMSNet Gateway

O **SMSNet Gateway** é um aplicativo Android que permite enviar mensagens SMS e RCS usando o seu próprio chip, integrando-se diretamente à plataforma [smsnet.com.br](https://smsnet.com.br). Essa integração combina a confiabilidade do seu dispositivo móvel com a robustez da API da SMSNet, oferecendo:

* **Envio de SMS e RCS**
  Utilize sua linha física para disparar mensagens de texto tradicionais (SMS) ou ricas (RCS), com entrega rápida e relatórios de status.

* **Autenticação simplificada**
  Cadastre o seu dispositivo Android apenas uma vez e comece a enviar sem precisar manter credenciais adicionais no seu back-end.

* **API REST completa**
  A plataforma SMSNet disponibiliza endpoints RESTful para envio de mensagens, consulta de status e gestão de filas — basta integrar ao seu sistema em qualquer linguagem.

* **Escalabilidade e flexibilidade**
  Integre a outros sistemas (ERP, CRM, aplicativos web) para disparos automáticos, campanhas de marketing ou notificações transacionais.

* **Monitoramento e logs detalhados**
  Acompanhe cada mensagem enviada diretamente no painel da SMSNet ou consulte logs locais no app para auditoria e troubleshooting.

---

### Recursos principais

1. **Registro de dispositivo**

   * Cadastro fácil via aplicativo, seguindo o guia de configuração em nosso blog.
   * Conexão segura entre o app e a plataforma SMSNet.

2. **Envio de mensagens**

   * Suporte a SMS (texto simples) e RCS (mensagens enriquecidas).
   * Parametrização de remetente, destinatário e payload (texto, mídia, botões).

3. **Relatório de entrega**

   * Callbacks assíncronos para informar status de envio/entrega.
   * Consulta manual via API ou painel web.

4. **Multi-sistema**

   * Exponha a API da SMSNet para o seu ERP, CRM, sistema interno ou qualquer plataforma que suporte chamadas HTTP.

---

### Capturas de Tela

Abaixo estão algumas etapas do processo de configuração e uso do app:

<table>
  <tr>
    <td align="center">
        <img src="https://blog.smsnet.com.br/wp-content/uploads/2020/04/instalar-protec-6.jpg" width="300"/>
    </td>
    <td align="center">
      <img src="https://blog.smsnet.com.br/wp-content/uploads/2020/04/instalar-protec-10.jpg" width="300"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://blog.smsnet.com.br/wp-content/uploads/2020/04/instalar-protec-11.jpg" width="300"/>
    </td>
    <td align="center">
      <img src="https://blog.smsnet.com.br/wp-content/uploads/2020/04/instalar-protec-12.jpg" width="300"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://blog.smsnet.com.br/wp-content/uploads/2020/04/instalar-protec-13.jpg" width="300"/>
    </td>
    <td align="center">
      <img src="https://blog.smsnet.com.br/wp-content/uploads/2020/04/instalar-protec-9.jpg" width="300"/>
    </td>
  </tr>
</table>

---

### Como começar

1. Acesse o tutorial de cadastro de dispositivo no blog:
   [https://blog.smsnet.com.br/android-cadastrando-dispositivo/](https://blog.smsnet.com.br/android-cadastrando-dispositivo/)
2. Configure sua chave de API e parâmetros no app.
3. Execute o app e injete seu chip para iniciar o envio de SMS e RCS!

Para mais detalhes, consulte a [documentação oficial da SMSNet](https://smsnet.com.br) e o nosso blog post de configuração.
