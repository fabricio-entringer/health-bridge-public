<p align="center">
  <img src="docs/banner.svg" alt="HealthBridge — do Apple Health para o Telegram, com um toque" width="860">
</p>

<p align="center">
  <b>Do Apple Health para o Telegram, com um toque.</b><br>
  App de iPhone pessoal · sem servidor · o seu bot, os seus dados
</p>

<p align="center">
  <img alt="Plataforma" src="https://img.shields.io/badge/iOS-17%2B-0A1120?style=for-the-badge&logo=apple&logoColor=white">
  <img alt="Destino" src="https://img.shields.io/badge/Telegram-destino-229ED9?style=for-the-badge&logo=telegram&logoColor=white">
  <img alt="Servidor" src="https://img.shields.io/badge/servidor-nenhum-2EA043?style=for-the-badge">
  <img alt="Analytics" src="https://img.shields.io/badge/analytics-zero-FF375F?style=for-the-badge">
</p>

<p align="center">
  <a href="#-o-que-é">O que é</a> ·
  <a href="#-o-que-o-app-faz">O que faz</a> ·
  <a href="#-o-que-o-app-não-faz">O que não faz</a> ·
  <a href="#-como-relatar-um-problema-ou-sugerir-algo">Como relatar</a> ·
  <a href="#️-como-acompanhar-o-seu-pedido">Acompanhar</a> ·
  <a href="#-privacidade">Privacidade</a>
</p>

---

## 👋 Bem-vindo

Este é o **espelho público do HealthBridge** — o canal aberto onde você relata bugs, tira dúvidas e sugere melhorias.

> **O código-fonte não fica aqui.** Este repositório existe para uma coisa só: conversar com quem usa o app. Toda issue aberta aqui é lida, classificada e respondida.

<p align="center">
  <a href="https://github.com/fabricio-entringer/health-bridge-public/issues/new"><b>🐞 Relatar um problema</b></a> ·
  <a href="https://github.com/fabricio-entringer/health-bridge-public/issues"><b>📋 Ver o que já foi relatado</b></a>
</p>

---

## 🩺 O que é

O **HealthBridge** é um app de iPhone que lê as métricas do **Apple Health** que você autorizar — passos, frequência cardíaca, peso, energia ativa e outras — e as envia para um ou mais **canais ou grupos do Telegram**, usando **o seu próprio bot**.

Sem servidor, sem backend, sem nuvem no meio: o app fala direto com o Telegram a partir do seu iPhone.

```
🍎 Apple Health  →  📱 HealthBridge  →  ✈️ Telegram
   (só o que          (um toque no        (os canais que
    você autorizar)    botão Enviar)       você cadastrar)
```

É um app **pessoal**, distribuído por TestFlight/sideload. Não está na App Store, não é multiusuário e não coleta nada sobre você.

---

## ✨ O que o app faz

| | |
|---|---|
| ✈️ **Envio com um toque** | Uma tela, um botão, o resultado por canal na hora. |
| 🎯 **Você escolhe as métricas** | Tipo a tipo. O app só lê o que o Apple Health autorizou. |
| 📡 **Vários canais de uma vez** | O mesmo relatório para todos os destinos cadastrados. |
| 🧯 **Falha isolada** | Se um canal falha, os outros recebem normalmente — e o motivo fica registrado. |
| 🗒️ **Histórico** | Uma entrada por envio, com data, métricas e o status de cada canal. |
| 🔑 **Token protegido** | O token do seu bot fica guardado com segurança no iPhone e nunca é exibido de volta. |
| ✍️ **Mensagem do seu jeito** | Texto de introdução, menção e formato (texto, Markdown ou JSON) configuráveis por canal. |
| 📅 **Período do envio** | Hoje, um dia específico ou um intervalo. |

---

## 🚫 O que o app **não** faz

Estas são decisões deliberadas de produto, não pendências. Saber disso antes economiza o seu tempo:

- **Não tem versão Android.** É um app iOS, e isso não está previsto para mudar.
- **Não está na App Store.** A distribuição é pessoal, por TestFlight/sideload.
- **Não é multiusuário.** Não há contas, login ou perfis de pessoas diferentes.
- **Não usa servidor nosso.** Nada dos seus dados passa por qualquer infraestrutura nossa — porque não existe nenhuma.
- **Não envia sozinho, em horário marcado.** O envio é sempre manual, iniciado por você.
- **Não mostra gráficos nem exporta CSV.** O app envia e registra; a análise fica com você, no destino.
- **Não escreve nada no Apple Health.** A permissão é apenas de leitura.

Pedido que esbarra em um desses pontos costuma ser recusado — mas **sempre com uma explicação concreta**, nunca com um "fora de escopo" seco. E alguns temas evoluem: se o seu caso for de fronteira, ele é marcado para avaliação em vez de ser fechado na hora.

---

## 🐞 Como relatar um problema ou sugerir algo

A forma mais rápida é **pelo próprio app**, que já preenche a versão e o modelo para você. Se preferir, [abra a issue aqui](https://github.com/fabricio-entringer/health-bridge-public/issues/new) — em português ou inglês, tanto faz.

<details>
<summary><b>O que faz um bom relato de bug</b> (clique para abrir)</summary>

<br>

1. **O que você fez** — a sequência de passos, na ordem.
2. **O que aconteceu** — o comportamento que você viu.
3. **O que você esperava** — como deveria ter sido.
4. **Versão do app e do iOS** — o app inclui isso automaticamente quando o relato sai de dentro dele.
5. **Print ou vídeo**, se der. Vale muito em problema de tela.

⚠️ **Antes de anexar um print:** confira se ele não mostra o token do seu bot, o `chat_id` dos seus canais ou métricas de saúde que você não quer tornar públicas. Este repositório é aberto — qualquer pessoa lê o que você publica aqui.

</details>

<details>
<summary><b>O que faz uma boa sugestão</b> (clique para abrir)</summary>

<br>

1. **O problema, não a solução.** "Perco tempo conferindo se enviei hoje" leva mais longe do que "coloque um selo verde no topo".
2. **Quando isso te atrapalha** — com que frequência, em que situação.
3. **Como você resolve hoje**, se resolve.

Uma sugestão bem descrita pode ser aceita mesmo quando a solução final for diferente da que você imaginou.

</details>

**Antes de abrir:** dá uma olhada nas [issues existentes](https://github.com/fabricio-entringer/health-bridge-public/issues). Se alguém já relatou o mesmo, comentar lá ajuda mais do que abrir outra — pedidos repetidos são agrupados em uma issue só.

---

## 🏷️ Como acompanhar o seu pedido

Toda issue recebe etiquetas que dizem, sem você precisar perguntar, em que pé ela está.

**Decisão da triagem**

| Etiqueta | O que significa |
|---|---|
| `triage: pending` | Ainda não foi analisada. |
| `triage: accepted` | Aceita. Entrou na fila de trabalho. |
| `triage: needs-info` | Falta alguma informação para decidir — a resposta está com você. |
| `triage: under-review` | Caso de fronteira, em avaliação. |
| `triage: duplicate` | Já existe uma issue sobre isso; a conversa foi centralizada lá. |
| `triage: out-of-scope` | Não será feito, com o motivo explicado no comentário. |

**Andamento (nas aceitas)**

| Etiqueta | O que significa |
|---|---|
| `status: queued` | Na fila. |
| `status: in-progress` | Saiu da fila e está sendo trabalhada. |
| `status: shipped` | Entregue — você é avisado na própria issue, com a versão. |
| `status: closed-unresolved` | Encerrada sem entrega, com a explicação do desfecho. |

---

## 🤝 O que você pode esperar

- **Toda issue é lida e respondida.** Nenhuma some no silêncio.
- **Recusa vem com motivo concreto** e, quando existe, com uma alternativa.
- **Nunca prometemos data.** "Aceito e na fila" é o máximo que dá para dizer com honestidade.
- **Quando é entregue, você fica sabendo** — na própria issue, com o que mudou e onde está disponível.
- **Se o problema voltar, reabra.** Issue fechada não é assunto encerrado.

---

## 🔒 Privacidade

- O app lê **apenas** os tipos de métrica que você autorizar, um a um, e **nunca escreve** no Apple Health.
- O **único destino de rede** é a API do Telegram, falando com **o seu bot**, para **os seus canais**.
- **Zero** analytics, telemetria ou serviços de terceiros.
- O token do seu bot fica guardado com segurança no iPhone — não vai para backup nem para a nuvem, e não há como exibi-lo ou exportá-lo.

---

## 🌍 English

**HealthBridge** is a personal iOS app that reads the Apple Health metrics you authorize and sends them to your own Telegram channels — on demand, with a single tap. No server, no backend, no third parties.

This repository is the **public mirror**: the source code is not here, but bug reports, questions and suggestions are very welcome. Feel free to [open an issue](https://github.com/fabricio-entringer/health-bridge-public/issues/new) in English — the labels above tell you exactly where your request stands.

---

<p align="center">
  <sub>Projeto pessoal de <a href="https://entringer.dev">Fabrício Entringer</a> · uso interno, não distribuído pela App Store</sub>
</p>
