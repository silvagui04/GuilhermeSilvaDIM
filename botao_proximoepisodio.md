# 🎬 Análise de Interface: Botão "Próximo Episódio" (Prime Video)

Estudo de caso e análise de usabilidade do botão **"Próximo episódio"** na plataforma Prime Video, com base nas qualidades de *Design de Interação*: **Affordances**, **Signifiers**, **Feedback** e **Acessibilidade**[cite: 2].

---

## INTRODUÇÃO

O elemento escolhido para esta análise é o botão **“Próximo episódio”** da interface do Prime Video. Este botão permite ao utilizador avançar para o episódio seguinte de uma série sem ter de regressar à página principal do conteúdo e selecionar manualmente o episódio pretendido.

É uma funcionalidade especialmente útil no contexto de visualização contínua (*binge-watching*), simplificando e acelerando a navegação[cite: 1].

---

### Que ações é que o elemento permite de facto?[cite: 2]

A ação principal é **avançar diretamente para o episódio seguinte da série**[cite: 1].

* **Comportamento:** Ao ser selecionado, o Prime Video inicia a reprodução do episódio seguinte (caso esteja disponível e ativo no contexto)[cite: 1].
* **Localização na Interface:** O botão surge normalmente durante a exibição dos créditos ou fixo junto aos controlo gerais de vídeo[cite: 1].

---

### Que ações *parece* permitir (*affordances*)?[cite: 2]

* **Aparência de Botão:** O formato tridimensional/destacado e o texto indicam claramente que o elemento pode ser clicado, tocado ou selecionado[cite: 1].
* **Correspondência com a Realidade:** A *affordance* percebida está totalmente alinhada com a ação real: o utilizador reconhece um elemento interativo e espera que, ao ativá-lo, o vídeo mude para o próximo episódio[cite: 1].
* **Representação Simplificada:** Caso seja representado apenas por um ícone isolado (sem texto), a intenção pode tornar-se menos evidente para utilizadores menos familiarizados[cite: 1].

---

### Que *signifiers* existem?[cite: 2]

Os *signifiers* sinalizam onde e como interagir[cite: 1]:

| Signifier | Função / Papel na Interface |
| :--- | :--- |
| 📝 **Texto "Próximo episódio"** | Comunica de forma explícita a ação do botão[cite: 1]. |
| ⏩ **Ícone de avanço** | Simbolo gráfico universal de "passar à frente"[cite: 1]. |
| 🔘 **Forma e contraste** | Destaque visual que sugere um componente clicável[cite: 1]. |
| 📍 **Posicionamento** | Situado junto aos controlos de reprodução ou sobre os créditos[cite: 1]. |
| ⏱️ **Contagem decrescente** | Sinaliza visualmente a transição automática iminente[cite: 1]. |

---

### Algum *signifier* contraria a forma?[cite: 2]

> ⚠️ **Potenciais Problemas de Usabilidade:**
>
> 1. **Pouca Visibilidade / Ocultação:** Se o botão aparecer apenas durante os créditos de forma discreta ou misturado com outros ícones, o utilizador pode não o notar ou não perceber que permite avançar[cite: 1].
> 2. **Autoplay Automático:** A presença de uma contagem decrescente para início automático pode causar ambiguidade: o utilizador pode não perceber que o vídeo vai avançar sozinho ou ter pouco tempo para cancelar a ação[cite: 1].
> 3. **Variação de Interface:** O comportamento varia conforme a versão da aplicação, o dispositivo (TV, Mobile, Web) e as definições de conta[cite: 1].

---

### Que *feedback* devolve, e quando?[cite: 2]

* **Confirmação de Ação:** Após a seleção, o *feedback* principal é a transição imediata para o ecrã do episódio seguinte, acompanhada pelo indicador de carregamento e o início da reprodução[cite: 1].
* **Feedback Antecipado:** Na reprodução automática, a animação da contagem decrescente funciona como *feedback* contínuo, informando o tempo restante até ao início do novo conteúdo[cite: 1].

---

### O que acontece quando existe alguma falha?[cite: 2]

#### Principais Cenários de Falha[cite: 1]:
- O botão não responder ao clique ou toque[cite: 1].
- Demora excessiva ou erro no carregamento do episódio[cite: 1].
- Seleção acidental por parte do utilizador[cite: 1].
- Início automático indesejado devido ao *autoplay*[cite: 1].

#### 💡 Resposta Ideal da Interface:
A interface deve fornecer mensagens claras de estado (ex.: *"A carregar o próximo episódio..."*) e, em caso de falha de rede ou sistema, disponibilizar a opção explícita de **"Tentar novamente"**[cite: 1].

---

### Funciona sem visão ou sem rato?[cite: 2]
