![OctanaSynth Banner](./assets/banner.png)

## Sobre este repositório

**Atenção:** Este repositório **não contém o código-fonte** do OctanaSynth, pois é um projeto de código fechado.

O objetivo deste espaço é servir como o canal oficial para a **distribuição das versões (`.apk`)** do aplicativo. Aqui você sempre encontrará a versão mais recente e estável para download.

---

## 📥 Baixar a Última Versão

Você pode baixar a versão mais recente do OctanaSynth diretamente pela seção de **Releases** deste repositório.

➡️ [**Clique aqui para ir para a página de Downloads**](https://github.com/ofelipevaz/octanasynth/releases)

---

## ✨ Principais Recursos

OctanaSynth transforma seu dispositivo Android em uma ferramenta de performance MIDI completa, gratuita e sem anúncios.

* **Motor de Áudio Profissional:** Construído com o motor [**FluidSynth**](https://github.com/FluidSynth/fluidsynth) e drivers de áudio de alta performance (Oboe/OpenSL ES) para garantir latência ultrabaixa e resposta instantânea ao toque.
* **Timbres e Layers Infinitos:** Importe um número ilimitado de SoundFonts (`.sf2`) e crie camadas (layers) com múltiplos instrumentos tocando simultaneamente.
* **Controle Total por Instrumento:** Ajuste individualmente volume, canais MIDI (permitindo múltiplos teclados), oitava, sensibilidade ao toque e modos de performance (ex: tocar apenas a nota mais grave).
* **Performance à Prova de Falhas:** Com o sistema de **reconexão automática**, uma desconexão acidental do cabo MIDI não interrompe sua performance. O **Modo Contínuo** mantém o áudio ativo mesmo com o app em segundo plano.
* **Mapeamento MIDI Avançado:** Mapeie qualquer função — troca de presets, volume, transpose, gain — para um botão, knob ou pedal do seu controlador MIDI.
* **Efeitos Integrados:** Adicione profundidade e profissionalismo ao seu som com efeitos de **Reverb** e **Chorus** totalmente ajustáveis.
* **100% Gratuito e Offline:** Todas as funcionalidades estão disponíveis gratuitamente, sem anúncios e funcionam perfeitamente sem conexão com a internet.

---

## 🚀 Sobre o Projeto e Construção

O OctanaSynth nasceu da necessidade de um sintetizador MIDI para Android que fosse ao mesmo tempo poderoso, flexível e, acima de tudo, confiável para performances ao vivo. A intenção é democratizar o acesso a uma ferramenta de nível profissional, sem custos, anúncios ou limitações.

Para alcançar a latência ultrabaixa e a estabilidade necessárias, o aplicativo foi construído com uma arquitetura robusta:
* **Linguagem Nativa:** Desenvolvido em Java com o SDK nativo do Android para máxima performance.
* **Motor de Áudio em C++:** O núcleo de processamento de áudio utiliza uma implementação customizada do [**FluidSynth**](https://github.com/FluidSynth/fluidsynth) via JNI (Java Native Interface), garantindo processamento de áudio em tempo real e com o mínimo de atraso.
* **Arquitetura Moderna:** Utiliza o padrão MVVM (Model-View-ViewModel) com componentes do Android Jetpack para uma interface reativa e um código organizado e manutenível.

---

## 🌐 Website Oficial

Para uma experiência mais visual e detalhada sobre o aplicativo, visite nosso site oficial.

**Tecnologias do site:**
O site foi construído com as tecnologias mais modernas para garantir uma experiência rápida e fluida:
* Next.js
* React
* Tailwind CSS
* Swiper.js

---

## 📜 Licença

Este é um software proprietário. Todos os direitos são reservados. A redistribuição ou engenharia reversa do aplicativo não é permitida.

> Este aplicativo foi construído com o auxílio da IA **Gemini** do Google, que foi fundamental no desenvolvimento de ideias, código e design.
