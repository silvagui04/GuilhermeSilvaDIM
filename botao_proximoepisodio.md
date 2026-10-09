# 🎬 Análise de Interface: Botão "Próximo Episódio" (Prime Video)

Estudo de caso e análise de usabilidade do botão **"Próximo episódio"** na plataforma Prime Video, com base nas qualidades de *Design de Interação*: **Affordances**, **Signifiers**, **Feedback** e **Acessibilidade**.

---

## INTRODUÇÃO

O elemento escolhido para esta análise é o botão **“Próximo episódio”** da interface do Prime Video. Este botão permite ao utilizador avançar para o episódio seguinte de uma série sem ter de regressar à página principal do conteúdo e selecionar manualmente o episódio pretendido.

É uma funcionalidade especialmente útil no contexto de visualização contínua (*binge-watching*), simplificando e acelerando a navegação.

---

### Que ações é que o elemento permite de facto?

A ação principal é **avançar diretamente para o episódio seguinte da série**.

* **Comportamento:** Ao ser selecionado, o Prime Video inicia a reprodução do episódio seguinte (caso esteja disponível e ativo no contexto)[cite: 1].
* **Localização na Interface:** O botão surge normalmente durante a exibição dos créditos ou fixo junto aos controlo gerais de vídeo.

---

### Que ações *parece* permitir (*affordances*)?

* **Aparência de Botão:** O formato tridimensional/destacado e o texto indicam claramente que o elemento pode ser clicado, tocado ou selecionado.
* **Correspondência com a Realidade:** A *affordance* percebida está totalmente alinhada com a ação real: o utilizador reconhece um elemento interativo e espera que, ao ativá-lo, o vídeo mude para o próximo episódio[cite: 1].
* **Representação Simplificada:** Caso seja representado apenas por um ícone isolado (sem texto), a intenção pode tornar-se menos evidente para utilizadores menos familiarizados[cite: 1].

---

### Que *signifiers* existem?

Os *signifiers* sinalizam onde e como interagir:

| Signifier | Função / Papel na Interface |
| :--- | :--- |
|  **Texto "Próximo episódio"** | Comunica de forma explícita a ação do botão. |
|  **Ícone de avanço** | Simbolo gráfico universal de "passar à frente". |
|  **Forma e contraste** | Destaque visual que sugere um componente clicável. |
|  **Posicionamento** | Situado junto aos controlos de reprodução ou sobre os créditos. |
|  **Contagem decrescente** | Sinaliza visualmente a transição automática iminente. |

---

### Algum *signifier* contraria a forma?

*  **Potenciais Problemas de Usabilidade:**
*
* 1. **Pouca Visibilidade / Ocultação:** Se o botão aparecer apenas durante os créditos de forma discreta ou misturado com outros ícones, o utilizador pode não o notar ou não perceber que permite avançar.
* 2. **Autoplay Automático:** A presença de uma contagem decrescente para início automático pode causar ambiguidade: o utilizador pode não perceber que o vídeo vai avançar sozinho ou ter pouco tempo para cancelar a ação.
* 3. **Variação de Interface:** O comportamento varia conforme a versão da aplicação, o dispositivo (TV, Mobile, Web) e as definições de conta.

---

### Que *feedback* devolve, e quando?

* **Confirmação de Ação:** Após a seleção, o *feedback* principal é a transição imediata para o ecrã do episódio seguinte, acompanhada pelo indicador de carregamento e o início da reprodução.
* **Feedback Antecipado:** Na reprodução automática, a animação da contagem decrescente funciona como *feedback* contínuo, informando o tempo restante até ao início do novo conteúdo.

---

### O que acontece quando existe alguma falha?

#### Principais Cenários de Falha:
- O botão não responder ao clique ou toque.
- Demora excessiva ou erro no carregamento do episódio.
- Seleção acidental por parte do utilizador.
- Início automático indesejado devido ao *autoplay*.

####  Resposta Ideal da Interface:
A interface deve fornecer mensagens claras de estado (ex.: *"A carregar o próximo episódio..."*) e, em caso de falha de rede ou sistema, disponibilizar a opção explícita de **"Tentar novamente"**.

---

### Funciona sem visão ou sem rato?
