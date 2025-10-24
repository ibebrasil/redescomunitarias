---
title: Home
slug: home
pageSettings:
  language: pt-BR
  link_pt_br: '#'
  link_en: '#'
  link_es: '#'
  animations: enable_all
  direction: left
  seoTitle: ''
  seoDescription: ''
pageTheme:
  primaryColor: '#000009'
  secondaryColor: '#ffffff'
  highlightColor: '#313232'
  auxiliaryColor: '#0f7c77'
  displayFont: ''
  textFont: ''
  spacingPatterns:
    - name: Teste
      mobile: '10'
      tablet: '11'
      desktop: '12'
mapbox:
  style: mapbox://styles/comborari/ckr4wi3k80fpl17qo34th6kk2
  token: pk.eyJ1IjoiY29tYm9yYXJpIiwiYSI6ImNrcjR3OWczMjBhaWEyeHIyaWhwMnUzNHcifQ.Yv7o7kj1ImyC9Rn-egF0TQ
  centerLng: '0'
  centerLat: '0'
  zoom: '0'
  bearing: ''
  pitch: ''
  layers: ''
  columnAlign: left
  floatingText: false
  views:
    - id: view_0
      centerLng: '0'
      centerLat: '0'
      zoom: '0'
      mobileZoom: ''
      duration: ''
      bearing: ''
      pitch: ''
      layers: ''
      title: ''
      notes: ''
      center:
        lng: -58.911
        lat: -6.315
      mobile:
        zoom: 3.5
      captions:
        title: false
        notes: false
        items:
          - icon: circle
            colorIcon: '#d37c17ff'
            typeIcon: outlined
            iconFill: true
            text: archaeologic sites
  center:
    lng: -54.875
    lat: -2.53
  mapView: ''
components:
  - type: Group
    id: cabecalho
    shortTitle: Cabeçalho
    longTitle: Cabeçalho
    description: ''
    showInMenu: false
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Custom
    customBgColor: '#4d4d58a1'
    backgroundMedia:
      - type: backgroundVideo
        videoSrc: /uploads/video_bg.mp4
    overlay: dark
    components:
      - type: ColumnSticky
        hasDropCap: false
        txtColor: ''
        bgColor: ''
        paddingTop: true
        paddingBottom: true
        layout: title-bottom
        title: PROJETOS DE REDES COMUNITÁRIAS DE SP E RJ
        components:
          - type: Text
            hasDropCap: false
            content: |-
              #### Apoio via Emendas Parlamentares

              Reunir e disponibilizar os **ofícios**, **espelhos de emenda** e **sumários executivos** dos projetos de redes comunitárias nos estados de São Paulo e do Rio de Janeiro, para apoio via emendas parlamentares.
            txtColor: ''
            bgColor: ''
            customBgColor: ''
            customTxtColor: ''
        body: ''
        customBgColor: ''
        customTxtColor: ''
    layout: default
  - type: Group
    id: introducao
    shortTitle: Introdução
    longTitle: Introdução
    description: ''
    showInMenu: true
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    overlay: dark
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                **Como será viabilizado**

                As emendas poderão ser direcionadas tanto ao **Ministério da Ciência, Tecnologia e Inovação (MCTI)&#32;**ou **Ministério das Comunicações (MCOM)**, utilizando **modalidade de aplicação 90** e **localizador 0001 – Nacional**. A(o) parlamentar poderá **oficiar ao respectivo minitério** as **localidades** onde os projetos serão implementados, priorizando **áreas rurais**, **periferias urbanas** e **povos e comunidades tradicionais** em situação de exclusão digital.

                **Quem promove**

                As propostas contam com o apoio do **Comitê Nacional de Redes Comunitárias**, com apoio do **Instituto Bem Estar Brasil (IBEBrasil)**. O IBEBrasil presta **incidência e suporte técnico** às **10 comunidades proponentes**, em um momento estratégico de debate do **Plano Nacional de Inclusão Digital**, que consolida as redes comunitárias como **política pública de inclusão digital** e **conectividade significativa** no âmbito federal.
            - type: VideoEmbed
              wideVideo: false
              videoUrl: https://www.youtube.com/embed/x47BLqD4onM?si=0yBPMvLOum67_EEn
              videoCaption: Redes Comunitárias de Internet - Projeto de Expansão na Baixada Campista e Sertão Sanjoanense
        column2:
          components:
            - type: BigNumbers
              alignment: caption-bottom
              items:
                - number: '10'
                  caption: Projetos
            - type: Text
              hasDropCap: false
              content: Abaixo, você encontra o resumo de cada projeto e os respectivos ofícios, espelhos de emenda e o sumário-base. - sumário executivo. Ou você pode baixar aqui todos os documentos juntos em um arquivo .zip para cada região.
            - type: Spacer
              desktop: 50px
              tablet: 50px
              mobile: 50px
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Projetos do RJ (6)
                    text: Todos os projetos de comunidades do Rio de Janeiro
                    link:
                      url: /projetos/uploads/Projetos_emendas_redes_comunitarias_RJ.zip
                      target: _blank
                      customTarget: ''
                      text: Baixar Documentos
                    icon: <span class="material-symbols-outlined"> download_2 </span>
                - Card:
                    type: Card
                    title: Projetos do SP (4)
                    text: Todos os projetos de comunidades do São Paulo
                    link:
                      url: /projetos/uploads/Projetos_emendas_redes_comunitarias_SP.zip
                      target: _blank
                      customTarget: ''
                      text: Baixar Documentos
                    icon: <span class="material-symbols-outlined"> download_2 </span>
    layout: default
  - type: Group
    id: barra_acu
    shortTitle: Barra do Açu
    longTitle: Barra do Açu
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Gallery
              description: Fotos da rede
              uniqid: g_barra_acu
              images:
                - image: /uploads/image45.jpg
                  caption: ''
                - image: /uploads/image18.jpg
                  caption: ''
                - image: /uploads/image7.jpg
                  caption: ''
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ## Barra do Açu

                Na Barra do Açu (São João da Barra/RJ), a expansão parte de uma rede já viva — 50 famílias conectadas e uma rádio web comunitária — para chegar a mais 250 famílias e a pontos como escola, praças, UBS e sede associativa. A governança comunitária liderada pela AMA, com rotinas de manutenção e formação de agentes locais, consolida uma infraestrutura de direitos em um território em transformação, fortalecendo comércio, turismo de base comunitária, canais próprios de comunicação e alerta.
            - type: Spacer
              desktop: 30px
              tablet: 30px
              mobile: 30px
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Documentos disponíveis
                    text: Sumário do projeto, o ofício e o espelho do pedido de emenda parlamentar.
                    link:
                      url: /projetos/uploads/BarradoAcu.pdf
                      target: _blank
                      customTarget: ''
                      text: Baixar
                    icon: ''
  - type: Group
    id: cazumba
    shortTitle: Cazumbá
    longTitle: Cazumbá
    description: ''
    showInMenu: true
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Custom
    customBgColor: '#926b16ff'
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/rural_meadow_landscape_background-900.jpg
    overlay: dark
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ## Cazumbá e entorno

                Em Cazumbá e entorno (Sabonete, Campos de Areia, Córrego Fundo, Barra do Jacaré e Água Preta), também em São João da Barra, o projeto conecta 250 famílias agricultoras e pontos coletivos — praças, duas unidades de saúde e três escolas — num município com baixa densidade de banda larga. A autogestão, com protagonismo da ADEC, sustenta o uso seguro e prático da rede (educação, saúde, documentos, alertas climáticos), reduz custos e assimetrias de informação e dá previsibilidade ao escoamento da produção, com efeito multiplicador no Sertão Sanjoanense.
            - type: Spacer
              desktop: 30px
              tablet: 30px
              mobile: 30px
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Documentos disponíveis
                    text: Sumário do projeto, o ofício e o espelho do pedido de emenda parlamentar.
                    link:
                      url: /projetos/uploads/Cazumba.pdf
                      target: _self
                      customTarget: ''
                      text: Baixar
                    icon: ''
        column2:
          components:
            - type: Gallery
              description: Fotos da rede
              uniqid: g_cazumba
              images:
                - image: /uploads/image12.jpg
                  caption: ''
                - image: /uploads/image24.jpg
                  caption: ''
                - image: /uploads/image11.jpg
                  caption: ''
  - type: Group
    id: marrecas_quixaba
    shortTitle: Marrecas e Quixaba
    longTitle: Marrecas e Quixaba
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Gallery
              description: Fotos da rede
              uniqid: g_marrecas
              images:
                - image: /uploads/image40.png
                  caption: ''
                - image: /uploads/image22.png
                  caption: ''
                - image: /uploads/image25.png
                  caption: ''
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ## Marrecas e Quixaba

                Na Baixada Campista, Marrecas e Quixaba expandem uma rede já ativa — hoje com 120 famílias — para alcançar mais 250 famílias (≈ 1.000 pessoas), além de duas praças e duas associações. Em território rural e disperso, a solução reforça backhaul quando necessário, amplia a última milha, instala Wi‑Fi comunitário e realiza atendimentos domiciliares, tudo sob gestão local simples e transparente. O impacto se vê no cotidiano: aulas híbridas, teleatendimento em saúde, emissão de documentos, boletins de tempo e maré para pesca e plantio, logística compartilhada e meios de pagamento digitais.
            - type: Spacer
              desktop: 30px
              tablet: 30px
              mobile: 30px
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Documentos disponíveis
                    text: Sumário do projeto, o ofício e o espelho do pedido de emenda parlamentar.
                    link:
                      url: /projetos/uploads/Marrecas.pdf
                      target: _blank
                      customTarget: ''
                      text: Baixar
                    icon: ''
  - type: Group
    id: espiritosantinho_garrafao_santarita
    shortTitle: Espírito Santinho, Garrafão e Santa Rita
    longTitle: Espírito Santinho, Garrafão e Santa Rita
    description: ''
    showInMenu: true
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Custom
    customBgColor: '#926b16ff'
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/rural_meadow_landscape_background-900.jpg
    overlay: dark
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ## Espírito Santinho, Garrafão e Santa Rita

                Nas comunidades rurais de Espírito Santinho, Garrafão e Santa Rita (Campos dos Goytacazes/RJ), a proposta conecta 250 famílias da agricultura familiar e ativa pontos coletivos (praças, sedes associativas e serviços locais), reforçando backhaul e última milha, com Wi‑Fi comunitário e atendimento residencial básico. Ao sustentar a vida no campo, a rede favorece estudo a distância, teleorientação em saúde, acesso a políticas públicas, previsões e alertas climáticos, organização da produção e canais de venda direta — reduzindo isolamento e ampliando renda e oportunidades.
            - type: Spacer
              desktop: 30px
              tablet: 30px
              mobile: 30px
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Documentos disponíveis
                    text: Sumário do projeto, o ofício e o espelho do pedido de emenda parlamentar.
                    link:
                      url: /projetos/uploads/ESantinho.pdf
                      target: _self
                      customTarget: ''
                      text: Baixar
                    icon: ''
        column2:
          components:
            - type: Gallery
              description: Fotos da rede
              uniqid: g_espiritossantinho
              images:
                - image: /uploads/image19.png
                  caption: ''
                - image: /uploads/image8.jpg
                  caption: ''
                - image: /uploads/image16.png
                  caption: ''
  - type: Group
    id: assentamento_25_marco
    shortTitle: Assentamento 25 de Março
    longTitle: Assentamento 25 de Março
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Gallery
              description: Fotos da rede
              uniqid: g_assentamento_25_marco
              images:
                - image: /uploads/image6.png
                  caption: ''
                - image: /uploads/image14.png
                  caption: ''
                - image: /uploads/image21.png
                  caption: ''
                - image: /uploads/image20.png
                  caption: ''
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ## Assentamento 25 de Março

                No Assentamento 25 de Março (Itaquira, Carapebus/RJ), o projeto trata conectividade como infraestrutura de direitos para 250 famílias e pontos coletivos (praça, sede da associação e serviços locais). A governança simples, com protagonismo da APRA 25 de Março, forma técnicos do próprio território e reativa parcerias com IFF e UENF, convertendo um plano interrompido na pandemia em ação estruturante que encurta distâncias para estudo e saúde, reduz custos e assimetrias de informação e fortalece a autonomia comunitária.
            - type: Spacer
              desktop: 30px
              tablet: 30px
              mobile: 30px
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Documentos disponíveis
                    text: Sumário do projeto, o ofício e o espelho do pedido de emenda parlamentar.
                    link:
                      url: /projetos/uploads/Carapebus.pdf
                      target: _blank
                      customTarget: ''
                      text: Baixar
                    icon: ''
  - type: Group
    id: comurede
    shortTitle: ComuREDE
    longTitle: ComuREDE
    description: ''
    showInMenu: true
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Custom
    customBgColor: '#926b16ff'
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/rural_meadow_landscape_background-900.jpg
    overlay: dark
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ## **ComuREDE**

                Projeto da **ComuREDE**, a iniciativa na E.M. Alberto Francisco Torres (Niterói/RJ) — com 338 estudantes e 31 profissionais — atua em área urbana periférica com favelas no entorno onde a exclusão digital é elevada: 43% dos lares não possuem internet fixa/adequada e, sob o critério de conectividade significativa, estima-se que apenas 20–40% tenham serviço compatível com educação e trabalho remoto; além disso, planos de R$ 70–130/mês consomem 8–16% de rendas per capita de R$ 600–1.200. Para reverter esse quadro, o projeto implementa redes comunitárias híbridas (rádio e fibra local) autogeridas pela comunidade escolar — modelo já validado em periferias urbanas, áreas rurais, indígenas e quilombolas — garantindo acesso confiável a custos justos, com formação e governança locais, habilitando ensino híbrido, serviços públicos digitais e maior dinamização econômica no território.
            - type: Spacer
              desktop: 30px
              tablet: 30px
              mobile: 30px
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Documentos disponíveis
                    text: Sumário do projeto, o ofício e o espelho do pedido de emenda parlamentar.
                    link:
                      url: /projetos/uploads/Niteroi.pdf
                      target: _self
                      customTarget: ''
                      text: Baixar
                    icon: ''
        column2:
          components:
            - type: Gallery
              description: Fotos da rede
              uniqid: g_niteroi
              images:
                - image: /uploads/image13.png
                  caption: ''
                - image: /uploads/image41.png
                  caption: ''
                - image: /uploads/image4.png
                  caption: ''
  - type: Group
    id: ribeirao_grande
    shortTitle: Ribeirão Grande
    longTitle: Quilombo Ribeirão Grande/Terra Seca
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Gallery
              description: Fotos da rede
              uniqid: g_ribeiraogrande
              images:
                - image: /uploads/image28.jpg
                  caption: ''
                - image: /uploads/image10.jpg
                  caption: ''
                - image: /uploads/image36.jpg
                  caption: ''
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ## Quilombo Ribeirão Grande/Terra Seca

                No Quilombo Ribeirão Grande/Terra Seca (Barra do Turvo/SP), onde o sinal “bate nos morros” e a densidade de banda larga é 23,4 por 100 habitantes, o projeto inicia com 30 famílias e pontos coletivos, já dimensionado para alcançar 150. A estratégia combina infraestrutura adequada ao relevo, gestão participativa e suporte técnico de agentes do próprio quilombo, convertendo acesso em cidadania: estudo, saúde, comercialização agroecológica e comunicação comunitária.
            - type: Spacer
              desktop: 30px
              tablet: 30px
              mobile: 30px
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Documentos disponíveis
                    text: Sumário do projeto, o ofício e o espelho do pedido de emenda parlamentar.
                    link:
                      url: /projetos/uploads/QuilomboRibeiraoGrandeTerraSeca.pdf
                      target: _blank
                      customTarget: ''
                      text: Baixar
                    icon: ''
  - type: Group
    id: heliopolis
    shortTitle: Heliópolis
    longTitle: Heliópolis - UNAS
    description: ''
    showInMenu: true
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Custom
    customBgColor: '#926b16ff'
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/rural_meadow_landscape_background-900.jpg
    overlay: dark
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ## Heliópolis - UNAS

                Em Heliópolis (São Paulo/SP), a rede comunitária se integra a uma trajetória de organização social que inclui UNAS, a Rádio Comunitária Heliópolis e o Museu Digital (UNAS/UFABC). A proposta conecta 250 famílias nas áreas de Heliópolis e Cidade Nova, com pontos de uso coletivo em vielas e praças, reforçando educação, teleorientação em saúde, qualificação profissional, microempreendedorismo e comunicação local — um passo a mais para que bolsões periféricos não sigam à margem, mesmo numa capital com indicadores médios mais altos.
            - type: Spacer
              desktop: 30px
              tablet: 30px
              mobile: 30px
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Documentos disponíveis
                    text: Sumário do projeto, o ofício e o espelho do pedido de emenda parlamentar.
                    link:
                      url: /projetos/uploads/Heliopolis.pdf
                      target: _self
                      customTarget: ''
                      text: Baixar
                    icon: ''
        column2:
          components:
            - type: Gallery
              description: Fotos da rede
              uniqid: g_heliopolis
              images:
                - image: /uploads/image47.jpeg
                  caption: ''
                - image: /uploads/image48.jpeg
                  caption: ''
                - image: /uploads/image50.jpeg
                  caption: ''
                - image: /uploads/image49.jpeg
                  caption: ''
  - type: Group
    id: novo_futuro
    shortTitle: Novo Futuro
    longTitle: Novo Futuro Jardim Peri
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Gallery
              description: Fotos da rede
              uniqid: g_novofuturo
              images:
                - image: /uploads/image33.jpg
                  caption: ''
                - image: /uploads/image37.jpg
                  caption: ''
                - image: /uploads/image17.jpg
                  caption: ''
                - image: /uploads/image42.jpg
                  caption: ''
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ## Novo Futuro Jardim Peri

                No Jardim Peri (zona norte de São Paulo), a Rede Comunitária Novo Futuro nasce de uma base social ativa (Associação Pipa) e enfrenta um diagnóstico claro: entre ~3 mil famílias da Favela Futuro Melhor, há 392 domicílios sem internet, mais de 1.200 barrados pelo preço e ~1.792 compartilhando uma mesma conexão por quatro ou mais pessoas. O projeto liga 250 famílias e espaços coletivos (campo, vielas e praças), com backhaul estável, hubs Wi‑Fi gerenciáveis, kits domiciliares e trilhas de habilidades digitais, para reduzir dependências externas e abrir caminhos de estudo, renda e pertencimento.
            - type: Spacer
              desktop: 30px
              tablet: 30px
              mobile: 30px
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Documentos disponíveis
                    text: Sumário do projeto, o ofício e o espelho do pedido de emenda parlamentar.
                    link:
                      url: /projetos/uploads/PIPA.pdf
                      target: _blank
                      customTarget: ''
                      text: Baixar
                    icon: ''
  - type: Group
    id: cozinhas_solidarias
    shortTitle: Cozinhas Solidárias MTST
    longTitle: Cozinhas Solidárias - Núcleo de Tecnologia do MTST
    description: ''
    showInMenu: true
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Custom
    customBgColor: '#926b16ff'
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/rural_meadow_landscape_background-900.jpg
    overlay: dark
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ## Cozinhas Solidárias - Núcleo de Tecnologia do MTST

                Projeto do **Núcleo de Tecnologia do MTST**, a iniciativa nas **Cozinhas Solidárias** transforma 12 unidades em São Paulo em hubs de inclusão digital, sem perder sua missão de garantir refeições diárias, gratuitas e saudáveis e de fortalecer laços comunitários. Em territórios onde a conectividade é cara, instável ou ausente e faltam dispositivos e formação crítica, o projeto instala infraestrutura estável (Wi‑Fi aberto interno e externo, link dedicado, roteadores e nobreaks), oferece capacitações contínuas e forma 36 agentes comunitários, com governança participativa, parcerias locais, reuso de equipamentos e suporte técnico para sustentabilidade. O alcance direto é de ~2.400 pessoas/dia, com internet disponível também no entorno de cada cozinha, materiais didáticos e oficinas para juventude, mulheres e cuidadores — conectando famílias a serviços públicos, oportunidades de trabalho e participação cidadã — fazendo de cada cozinha uma infraestrutura de direitos: **prato cheio, conexão segura e futuro possível**.
            - type: Spacer
              desktop: 30px
              tablet: 30px
              mobile: 30px
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Documentos disponíveis
                    text: Sumário do projeto, o ofício e o espelho do pedido de emenda parlamentar.
                    link:
                      url: /projetos/uploads/MTST-CozinhasSolidarias.pdf
                      target: _self
                      customTarget: ''
                      text: Baixar
                    icon: ''
        column2:
          components:
            - type: Gallery
              description: Fotos da rede
              uniqid: g_mtst
              images:
                - image: /uploads/image46.png
                  caption: ''
                - image: /uploads/image26.png
                  caption: ''
                - image: /uploads/image3.png
                  caption: ''
                - image: /uploads/image5.jpg
                  caption: ''
                - image: /uploads/image44.jpg
                  caption: ''
                - image: /uploads/image27.jpg
                  caption: ''
  - type: Group
    id: videos
    shortTitle: Videos
    longTitle: Videos
    description: ''
    showInMenu: false
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Primary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ### Saiba mais sobre as Redes Comunitárias

                Veja vídeos de projetos, organizações e comunidades que promovem Redes Comunitárias conhecer mais esse movimento que promove autonomia tecnológica.
        column2:
          components:
            - type: InnerColumns
              column1:
                components:
                  - type: VideoEmbed
                    wideVideo: false
                    videoUrl: https://www.youtube.com/embed/VS_VwtzCd7g?si=YRveHp9kJL-B0Fws
                    videoCaption: Redes Comunitárias de Internet - Projeto de Expansão na Baixada Campista e Sertão Sanjoanense
                  - type: VideoEmbed
                    wideVideo: false
                    videoUrl: https://www.youtube.com/embed/mb_AMyBn80k?si=F1XPT77He4H_Kj6p
                    videoCaption: Cultivando uma rede comunitária no quilombo Ribeirão Grande/Terra Seca
              column2:
                components:
                  - type: VideoEmbed
                    wideVideo: false
                    videoUrl: https://www.youtube.com/embed/x47BLqD4onM?si=Fc55HnJ2pnxmd5ny
                    videoCaption: Redes Comunitárias de Internet - Projeto de Expansão na Baixada Campista e Sertão Sanjoanense
                  - type: VideoEmbed
                    wideVideo: false
                    videoUrl: https://www.youtube.com/embed/BFyUNaMeCW8?si=CYS5KtQQYwvn3DtS
                    videoCaption: 'II Encontro de Redes Comunitárias de Internet: um balanço do encontro pela democratização do acesso'
  - type: Group
    id: links
    shortTitle: Links
    longTitle: Links
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '### Links relacionados'
        column2:
          components:
            - type: Spacer
              desktop: 1px
              tablet: 1px
              mobile: 1px
      - type: CardsCall
        cardsCallArr:
          - link:
              url: https://www.gov.br/anatel/pt-br/regulado/universalizacao/redes-comunitarias
              target: _blank
              customTarget: ''
            img:
              src: /uploads/screenshot-from-2025-10-23-13-09-22.png
              alt: ''
            title: Grupo de Trabalho de Redes Comunitárias na Anatel
            text: A expansão das redes às áreas urbanas desatendidas, rurais ou remotas tem sido um princípio norteador da ampliação de acesso no país. Tanto o mercado como o governo apresentaram nos últimos anos iniciativas nesse sentido, como o aumento da presença das Prestadoras de Pequeno Porte (PPP) em pequenos municípios, a criação do Comitê das PPP (Resolução da Anatel nº 698/2018) ...
          - link:
              url: https://www.intgovforum.org/en/content/dynamic-coalition-on-community-connectivity-dc3-0
              target: _blank
              customTarget: ''
            img:
              src: /uploads/screenshot-from-2025-10-23-13-10-09.png
              alt: ''
            title: Dynamic Coalition Community Conectivity/ONU/IGF
            text: 'The need for a Dynamic Coalition on Community Connectivity (DC3) emerged during the IGF workshop 223 "Community Networks: a Revolutionary Paradigm", held in João Pessoa, during the 10th IGF. Workshop participants agreed on the potential of community networks in order to promote sustainable Internet connectivity...'
          - link:
              url: https://cetic.br/media/docs/publicacoes/7/20220905125048/estudos_setoriais_redes_comunitarias_de_internet_no_brasil.pdf
              target: _blank
              customTarget: ''
            img:
              src: /uploads/screenshot-from-2025-10-23-13-12-54.png
              alt: ''
            title: 'Estudos Setoriais: Redes Comunitárias de Internet no Brasil/CETIC.Br/CGI.Br'
            text: Há 17 anos, o Centro Regional de Estudos para o Desenvolvimento da Sociedade da Informação (Cetic.br), depa r t a mento do Núcleo de Informação e Coordenação do Ponto BR (NIC.br), monitora a apropriação das tecnologias digitais pela sociedade brasileira ...
          - link:
              url: https://www.gov.br/mcom/pt-br/noticias/2024/abril/inclusao-digital-em-areas-remotas-e-tema-de-reuniao-do-ministerio-das-comunicacoes-e-comite-de-redes-comunitarias
              target: _blank
              customTarget: ''
            img:
              src: /uploads/screenshot-from-2025-10-23-13-09-22.png
              alt: ''
            title: Reunião do Comitê Nacional de Redes Comunitárias com a Ministra Sônia Faustino do MCOM
            text: O Ministério das Comunicações recebeu nesta quarta-feira (17) representantes do Comitê de Redes Comunitárias. O grupo discutiu a implementação de políticas públicas voltadas à inclusão digital em áreas remotas através de redes comunitárias...
          - link:
              url: https://cetic.br/media/docs/publicacoes/7/20240415183307/estudos_setoriais-conectividade_significativa.pdf
              target: _blank
              customTarget: ''
            img:
              src: /uploads/screenshot-from-2025-10-23-17-58-54.png
              alt: ''
            title: Estudos Setoriai de Conectividad Significativa
            text: O papel desempenhado pela Internet em nosso cotidiano é cada vez mais relevante, embora sua presença seja, por vezes, menos perceptível. Essa mudança na compreensão se deve a quão imbricadas estão as tecnologias em nossas rotinas, de maneira que as fronteiras de sua presença ficam difusas...
---

