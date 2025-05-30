**W\.A.L.D.O.**
**Localização e Determinação de Objetos Detectáveis em Baixa Altitude**
-----------------------------------------------------------------------

## /!\ Atenção: as versões mais recentes do modelo estão disponíveis no Hugging Face [aqui](https://huggingface.co/StephanST/WALDO30)

[![Prévia do WALDO 3.0](https://i.imgur.com/hGghrLn.jpeg)](https://www.youtube.com/watch?v=1y5y9yklj2U)

## **Bem-vindo ao lançamento público do WALDO v3.0**

### O QUE É O WALDO?

WALDO é um modelo de inteligência artificial para detecção, baseado em uma robusta estrutura YOLO-v8 e em um pipeline próprio de dados sintéticos.
**O modelo é capaz de detectar as seguintes classes de objetos em imagens aéreas capturadas a partir de aproximadamente 9 metros de altitude até imagens de satélite!**

**Classes de saída:**

0 → ‘VeículoLeve’ → todos os tipos de automóveis civis, incluindo picapes, vans etc. 🚗🏎️🚓🚐🚑
1 → ‘Pessoa’ → pessoas em geral, inclusive em bicicletas ou nadando no mar 🧍‍♀️🕺💃🧜🏽‍♀️🏂🧞
2 → ‘Edificação’ → todos os tipos de construções 🕌🏛️🏭🏡
3 → ‘Poste’ → postes de energia, de utilidade pública ou qualquer estrutura vertical fina que deva ser evitada por drones 🎏
4 → ‘Embarcação’ → barcos, navios, canoas, caiaques, pranchas de surfe etc. 🚢🏄
5 → ‘Bicicleta’ → bicicletas, ciclomotores, motocicletas e afins 🚲
6 → ‘Contêiner’ → contêineres de carga, inclusive sobre caminhões articulados 📦🏗️
7 → ‘Caminhão’ → veículos comerciais de grande porte, incluindo caminhões articulados e baús sobre chassis 🚚
8 → ‘TanqueDeGás’ → tanques cilíndricos como botijões de gás ou silos de grãos 🫙
10 → ‘Escavadeira’ → veículos de construção como tratores, retroescavadeiras, etc. 🚜
11 → ‘PainéisSolares’ → painéis solares ▪️🌞▪️
12 → ‘Ônibus’ → ônibus 🚌

> Em geral, quanto menor o número da classe, melhor treinado está o modelo para aquela categoria.
>
> Para usuários de versões anteriores: observe que as classes de uso militar e detecção de fumaça foram removidas. Este projeto é um software livre voltado para aplicações civis e não se destina a fins militares.

---

### ONDE ESTÁ O WALDO?

Disponível no Hugging Face: [https://huggingface.co/StephanST/WALDO30](https://huggingface.co/StephanST/WALDO30)

Há também versões ligeiramente otimizadas disponíveis à venda no Gumroad:
[https://6228189440665.gumroad.com/l/WALDOv3](https://6228189440665.gumroad.com/l/WALDOv3)
Essas versões estão à venda como forma de patrocínio ao projeto. Se o modelo gratuito for útil para você, considere adquirir a versão aprimorada — mas a escolha é inteiramente sua.

\[![Melhoria de desempenho no modelo P2](https://i.imgur.com/VKa5NN5.png)]

Os arquivos seguem a licença MIT e podem ser compartilhados livremente, inclusive para uso comercial. A venda visa apenas compensar os custos de desenvolvimento e manter o projeto como software livre.

---

### PARA QUE SERVE?

Atualmente, o WALDO está sendo utilizado em:

1. Ações de resposta a desastres naturais
2. Monitoramento de reservas naturais (detecção de intrusos)
3. Cálculo de ocupação (estacionamentos, por exemplo)
4. Monitoramento de infraestrutura
5. Acompanhamento de obras
6. Gestão de fluxo de tráfego
7. Contagem de multidões
8. Aplicações artísticas com IA
9. Segurança em voos de drones (evitando pessoas/veículos no solo)
10. Muitas outras aplicações criativas...

A principal motivação para disponibilizar o WALDO gratuitamente é justamente acompanhar essas incríveis utilizações. Compartilhe comigo o que você construiu!

---

### PARA ENTUSIASTAS DE IA

Conjunto de modelos YOLOv8 treinados com base em dados sintéticos e semi-sintéticos próprios.
No momento, o conjunto de dados não será divulgado.

Os pesos estão totalmente abertos, possibilitando ampla flexibilidade de implantação!

---

### COMO COMEÇAR COM O WALDO?

Consulte o código de exemplo disponível no repositório para executar os modelos e obter resultados visuais usando a excelente biblioteca de anotações **Supervision**, da Roboflow.

---

### APROFUNDANDO

Se você já tem experiência com implantação de modelos de IA, pode:

1. Realizar o *fine-tuning* (ajuste fino) com seus próprios dados
2. Desenvolver um sistema de inferência com janela deslizante otimizado para seu hardware local
3. Quantizar os modelos para obter desempenho extremo em dispositivos simples
4. Utilizar os modelos para rotular dados e treinar seus próprios algoritmos!

Aproveite!

---

### VERSÕES ANTERIORES

As versões anteriores foram descontinuadas. Esta é a única que permanecerá disponível online.

---

### PRECISA DE AJUDA COM ALGO?

Claro! Entre em contato por e-mail:
📧 [stephan.sturges@gmail.com](mailto:stephan.sturges@gmail.com)

---

### A DETECÇÃO DE ‘X’ NÃO ESTÁ FUNCIONANDO COMO ESPERADO?

Envie exemplos de imagens, vídeos ou amostras de dados para:
📧 [stephan.sturges@gmail.com](mailto:stephan.sturges@gmail.com)

---

### APOIE O PROJETO WALDO!

Visite a [página do WALDO no Gumroad](https://t.co/kRvhYkVxW2) para apoiar o desenvolvimento!

---

### LICENÇA

Salvo indicação em contrário, todo o código desta versão é distribuído sob a licença a seguir:

---

**Licença MIT**

Copyright (c) 2024 Stephan Sturges / Aircortex.com

Permissão concedida, gratuitamente, a qualquer pessoa que obtenha uma cópia deste software e dos arquivos de documentação associados (“Software”), para utilizar o Software sem restrições, incluindo, sem limitação, os direitos de usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias do Software, e permitir que outras pessoas a quem o Software for fornecido o façam, sujeitas às seguintes condições:

O aviso de copyright acima e esta permissão deverão ser incluídos em todas as cópias ou partes substanciais do Software.

O SOFTWARE É FORNECIDO “NO ESTADO EM QUE SE ENCONTRA”, SEM GARANTIAS DE QUALQUER TIPO, EXPRESSAS OU IMPLÍCITAS, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS DE COMERCIALIZAÇÃO, ADEQUAÇÃO A UM FIM ESPECÍFICO E NÃO INFRAÇÃO. EM NENHUMA HIPÓTESE OS AUTORES OU DETENTORES DOS DIREITOS AUTORAIS SERÃO RESPONSÁVEIS POR QUALQUER RECLAMAÇÃO, DANO OU OUTRA RESPONSABILIDADE, SEJA EM AÇÃO CONTRATUAL, DELITUAL OU DE OUTRA NATUREZA, DECORRENTE DE, OU RELACIONADA AO USO OU OUTRAS FORMAS DE INTERAÇÃO COM O SOFTWARE.

---
