---
title: 'Pesquisa de mercado: viabilidade do robo-qlearning'
type: 'market'
topic: 'viabilidade robo-qlearning'
decision: 'Levar ou não o robo-qlearning ao mercado; em que formato (kit físico, só virtual, formação) e a que preço'
source: 'run'
status: complete
preset: 'standard'
validation: 'normal'
created: '2026-10-15'
updated: '2026-10-15'
claims_verified: 8
claims_unverified: 13
claims_disputed: 1
---

# Pesquisa de mercado: viabilidade do robo-qlearning

**Decisão que esta pesquisa apoia:** levar ou não o robo-qlearning ao mercado; em que formato (kit físico, só virtual, formação) e a que preço.

## Resumo executivo

**Veredito: viável, mas não começando pela venda de kit para a rede pública.** O caminho com mais chance é este:
1. Simulador e material de aula grátis, para ganhar uso e reputação.
2. Venda de "kit + formação" em pequenas tiragens para escolas privadas, SESI e espaços maker, com o produto rotulado para 14 anos ou mais.
3. Rede pública só por meio de um parceiro que já tenha CNPJ, selo Inmetro e experiência em licitação.

Três achados sustentam o veredito:

- **A demanda tem prazo e verba atrelada.** A computação entra no currículo obrigatório a partir de 2026 [8][5]. No Ensino Médio, um dos eixos de habilidades inclui fundamentos de IA [9]. Parte do Fundeb (o complemento VAAR) de 2026 depende de as redes terem referenciais curriculares de computação [6][7]. As redes precisam de material, e IA "mão na massa" em português quase não existe.
- **O nicho "robô que aprende por reforço" está vazio.** Os kits de desvio de obstáculos à venda funcionam por regras fixas [30]. A AWS desligou em 2025 o portal estudantil do DeepRacer, que ensinava aprendizado por reforço [18]. O material de Q-learning com robô para sala de aula que encontrei está em espanhol [27]. O diferencial do projeto é real.
- **O preço de R$ 600 a 900 cabe no mercado, mas a rede pública compra de outro jeito.** Compras públicas recentes ficaram perto de R$ 600 por kit [1]. Kits ESP32 com aulas prontas custam cerca de R$ 2.200 [17], e o LEGO SPIKE Prime cerca de R$ 5.200 [16]. Só que a rede pública compra por licitação, com especificação técnica, às vezes exigindo selo Inmetro [15], e sob fiscalização do TCU por sobrepreço [3][4]. Isso está fora do alcance de um professor vendendo sozinho.

**Maior ressalva:** o enquadramento no Inmetro não está confirmado. Produtos com função de brincadeira para crianças de até 14 anos exigem certificação compulsória [13], e alunos do 8º ano têm 13 ou 14 anos. Antes de vender, é preciso confirmar no Inmetro se o produto, rotulado para 14+ e como equipamento didático, fica fora do regulamento de brinquedos.

## 1. Tamanho e ritmo do mercado alcançável

Não encontrei um número publicado de tamanho de mercado para robótica educacional no Brasil, e isso já é um achado. Os sinais de volume vêm de compras públicas:

- **Paraná:** comprou mais 3.000 kits de robótica por cerca de R$ 1,8 milhão, com recursos do FNDE. A conta dá cerca de R$ 600 por kit (cálculo próprio) [1]. Confiança média.
- **Prefeituras em 2026:** fizeram compras desde 5 kits (cerca de R$ 7.260 por kit, em Maravilha-SC) [2] até lotes de quase R$ 1,8 milhão. Confiança média.

O motor da demanda é regulatório:
- **Resolução CNE/CEB nº 2/2025:** põe a educação digital e midiática no currículo de todas as etapas, em escolas públicas e privadas, com implementação a partir de 2026 [5]. Confiança alta.
- **Lei 14.533/2023 (Política Nacional de Educação Digital):** cita computação, programação e robótica como parte da educação digital [6]. Confiança média.
- **Estados já em movimento:** Minas Gerais criou o componente Educação Digital no Ensino Médio a partir de 2026, com programação e IA no referencial [10][11]. Confiança alta.
- **Fundeb:** a Resolução CIF nº 15/2025 condiciona o complemento VAAR de 2026 aos referenciais de computação [6][7]. Confiança média.

Há uma afirmação **disputada**: a de que "a robótica é obrigatória e a escola que não cumprir perde o Fundeb" [12]. Ela exagera o texto legal, que liga a verba ao currículo de computação, não à robótica em si.

**Mercado alcançável para você:**
- **Já ao seu alcance:** as suas turmas da SEDUC-SP e do SESI.
- **Primeiro alvo de venda:** escolas privadas e redes como o SESI, que compram sem licitação.
- **Mais adiante:** a rede pública, que exige licitação.

## 2. Quem compra e como decide

| Comprador | Como compra | O que valoriza |
|---|---|---|
| Rede estadual ou municipal | Licitação com estudo técnico, registro de preços e PNCP [2][1]. Alguns editais exigem selo Inmetro [15] | Preço por kit, conformidade, alinhamento à BNCC |
| SESI e escolas privadas | Compra direta ou orçamento | Material pronto, formação do professor, diferencial pedagógico |
| Professor individual | Do próprio bolso, em pequena escala | Gratuidade e facilidade |

Um gargalo aparece de novo em várias fontes: o avanço da robótica na escola depende de formar o professor [29]. Por isso o material de aula e a formação contam tanto quanto o robô.

## 3. Dores e necessidades não atendidas

- **Falta IA "mão na massa" em português para a escola.** O complemento de computação da BNCC não especifica habilidades de IA no Ensino Fundamental [31]. A atividade de Q-learning com robô que encontrei está em espanhol [27].
- **Kits proprietários são caros para a rede pública.** É essa a justificativa de projetos acadêmicos de baixo custo com impressão 3D, como o RoboXperience [26].
- **Compras mal feitas.** O TCU apontou indícios de sobrepreço e de especificação ruim em R$ 26 milhões de kits em Alagoas, entregues a escolas sem a infraestrutura necessária [3][4]. Confiança alta. Um kit simples, que funciona sem internet e vem com material de aula, responde a essa dor.
- **Viabilidade em sala:** um robô educacional com Q-learning aprende a tarefa em menos de 100 iterações [28]. Isso cabe numa aula. Confiança média.

## 4. Concorrência e substitutos

| Alternativa | Preço | Ensina aprendizado por reforço? | Observação |
|---|---|---|---|
| LEGO SPIKE Prime Set | R$ 5.263 [16] | Não, de fábrica | Referência de qualidade, muito caro |
| ACEBOTT ESP32 (com 16 aulas e slides) | R$ 2.207 [17] | Não | Já vende "kit + material do professor" |
| Kits de desvio de obstáculos com Arduino | US$ 67 a 82 [30] | Não, funciona por regras | Hardware parecido com o seu, sem a parte de IA |
| Kits da compra do Paraná | cerca de R$ 600 [1] | Não informado | Referência de preço público |
| SIMROBÓTICA (Sorocaba) | Não informado | Assistente de IA para o professor, não aprendizado do robô | Testado numa escola municipal até dez/2025 [21] |
| Teachable Machine (Google) | Grátis [19] | Não: ensina aprendizado supervisionado | **Concorre diretamente com o seu Robô 2** |
| IBM + Catavento "IA EDU" | Grátis [20] | Ensina aprendizado de máquina para 9 a 14 anos | Material virtual gratuito |
| AWS DeepRacer Student | Encerrado em set/2025 [18] | Ensinava | Deixou um espaço vago |
| Cursos de IA para professores (MEC, UFRN, UFPR) | Grátis [22][23] | Teoria | Formação de professores em IA já é oferecida de graça |

**Leitura:** não encontrei nenhum concorrente físico que ensine aprendizado por reforço com material em português. Por outro lado, a "versão só virtual" disputa espaço com bastante coisa gratuita e de marca forte (Google, IBM, MEC). Cobrar do professor por um simulador será difícil.

## 5. Preço e canais de venda

- **Faixa de preço:** um kit de R$ 600 a 900 fica abaixo dos kits ESP32 com aulas (R$ 2.200) [17] e muito abaixo do LEGO [16]. Fica perto do que um governo estadual pagou em grande volume [1]. Com custo de materiais de R$ 230 a 410, a margem bruta seria de 35% a 60% antes de embalagem, frete, impostos e suporte. É apertado, mas não inviável. A planilha por tiragem vai mostrar onde fica o ponto de equilíbrio.
- **Canais:**
  - **Direto:** as suas turmas, o SESI e escolas privadas.
  - **Parceria:** um fabricante ou distribuidor que já venda para governos e licencie o conteúdo e o projeto.
  - **Formação paga:** oficinas para escolas privadas. Não encontrei preços públicos de mercado para isso; é uma lacuna em aberto.

## Riscos de produto

- **Bateria 18650:** pode superaquecer, explodir ou pegar fogo se mal usada, e há células falsificadas e sem proteção no mercado [24][25]. Confiança alta. Robôs escolares concorrentes aceitam pilhas AA recarregáveis (NiMH) como alternativa [24]. Para vender, troque a 18650 por AA NiMH ou por um power bank USB.
- **Inmetro:** veja a ressalva do resumo [13][14]. Num kit com itens sujeitos a regulamentos diferentes, cada item segue a sua própria regra [14].

## Conclusões que só aparecem juntando os temas

- **Mesma brecha, duas razões.** O nicho de aprendizado por reforço está vazio, e a obrigação da computação começa em 2026. Juntas, elas abrem uma janela de 1 a 2 anos em que as redes procuram material de IA.
- **Mesmo público, dois problemas resolvidos.** Rotular o produto para 14 anos ou mais e trocar a 18650 por pilhas AA ataca de uma vez o risco regulatório e o de segurança. Isso tira o 8º ano mais novo do público do kit físico, mas o simulador continua servindo a ele.
- **O grátis é o canal, não o produto.** Num mercado cheio de opções gratuitas, o simulador gratuito funciona como divulgação. O que se vende é o que não existe de graça: o robô físico com aprendizado por reforço, material de aula pronto e formação.

## Recomendações

1. **Publique o simulador e o material de aula de graça e meça o uso** (GitHub Pages, já preparado). Confiança alta: há muitas opções gratuitas [19][20][22], e a sua vantagem está no aprendizado por reforço. *Alimenta o brief: problema e público.*
2. **Valide em sala antes de vender:** suas turmas do SESI e da SEDUC, com as 3 fichas. Registre o antes e o depois do aprendizado e publique como relato de experiência (por exemplo, na Revista DoCEntes), o que dá credibilidade. Confiança média.
3. **Mude o produto físico para venda:** pilhas AA NiMH no lugar da 18650, rótulo "14+ / equipamento didático" e consulta formal ao Inmetro. Confiança média, porque a portaria vigente não foi confirmada [13][15].
4. **Primeiro cliente pagante: escola privada, SESI ou espaço maker, com o pacote "kit + formação"** de 10 a 50 unidades. Confiança média: a faixa de preço se apoia em [1][16][17].
5. **Rede pública só com parceiro** que tenha CNPJ, selo Inmetro e experiência em licitação. O seu papel seria licenciar o conteúdo e o projeto. Confiança média [3][15].
6. **Robô 2: diferencie-se do Teachable Machine** [19]. Ele treina modelos na tela; o seu Robô 2 deve mostrar o aprendizado supervisionado mudando o comportamento do robô no mundo físico.

## Perguntas em aberto

- **Qual portaria do Inmetro vale hoje, e um kit didático rotulado 14+ fica fora dela?** Para responder: consulta ao Inmetro ou a um organismo certificador.
- **Quanto se cobra no mercado por formação ou oficina de IA para escola privada?** Para responder: pedir orçamentos a empresas de formação, ou fazer uma pesquisa com coordenadores.
- **As redes podem usar o PDDE para comprar kits em 2026?** Para responder: ler as resoluções vigentes do FNDE.
- **Qual é o custo real por tiragem (1, 10 e 50 kits), com impostos e frete?** Para responder: a planilha de custo e preço que já está planejada.

## Fontes

| n | Afirmação que sustenta | Publicador | Data | Acesso | Confiança |
|---|---|---|---|---|---|
| 1 | 3.000 kits por cerca de R$ 1,8 mi (FNDE) | [Governo do Paraná](https://www.parana.pr.gov.br/Audio/Escolas-estaduais-de-educacao-em-tempo-integral-recebem-mais-3-mil-kits-de-robotica) | 2025 | 2026-10-15 | média |
| 2 | 5 kits por R$ 36.305 em Maravilha-SC | [Alerta Licitação / PNCP](https://alertalicitacao.com.br/!licitacao/PNCP-82821190000172-1-000864-2026) | 2026 | 2026-10-15 | média |
| 3 | TCU: indícios de sobrepreço em kits em AL | [Folha de Pernambuco](https://www.folhape.com.br/politica/escolas-sem-agua-e-computador-receberam-r-26-milhoes-para-comprar/222637/) | s.d. | 2026-10-15 | alta |
| 4 | TCU: irregularidades em kits em AL | [DPL News](https://dplnews.com/?p=190858) | s.d. | 2026-10-15 | alta |
| 5 | Resolução CNE/CEB 2/2025 | [ABMES](https://abmes.org.br/legislacoes/detalhe/5057/resolucao-cne-ceb-n-2) | 2025-03 | 2026-10-15 | alta |
| 6 | PNED (Lei 14.533/2023) e CIF 15/2025 | [Prefeitura de Trajano de Moraes](https://www.trajanodemoraes.rj.gov.br/files/public/YXJxdWl2b3MvaW5zdGl0dWNpb25hbC84MzgwYzg3OC1iNDNlLTRmYWUtYTVjYi0zZGU2M2IzN2MwMDkucGRm) | s.d. | 2026-10-15 | média |
| 7 | Resolução municipal sobre BNCC Computação e VAAR | [Palmeira dos Índios](https://palmeiradosindios.al.gov.br/wp-content/uploads/2026/03/Resolucao-CMEPI-15-2025-BNCC-Computacao-DOM.pdf) | 2026-03 | 2026-10-15 | média |
| 8 | BNCC Computação obrigatória a partir de 2026 | [SBC (WEI)](https://sol.sbc.org.br/index.php/wei/article/download/43131/42897/) | s.d. | 2026-10-15 | média |
| 9 | Eixo de IA no Ensino Médio | [SBC (WIE)](https://sol.sbc.org.br/index.php/wie/article/download/26362/26185) | s.d. | 2026-10-15 | média |
| 10 | MG: componente Educação Digital a partir de 2026 | [Itatiaia](https://www.itatiaia.com.br/ouropreto/minas-gerais-oficializa-curriculo-de-computacao-e-fortalece-educacao-digital-nas-escolas/) | s.d. | 2026-10-15 | alta |
| 11 | MG: referencial com programação e IA | [Agência Minas](https://www.agenciaminas.mg.gov.br/news/pdf/128503.pdf) | s.d. | 2026-10-15 | alta |
| 12 | "Robótica obrigatória sob pena de perder Fundeb" (disputada) | [Super Rádio Tupi](https://www.tupi.fm/?p=2434616) | s.d. | 2026-10-15 | baixa |
| 13 | Selo Inmetro compulsório para brinquedos de até 14 anos | [Agência Brasil](https://agenciabrasil.ebc.com.br/geral/noticia/2022-06/regulamento-para-brinquedos-no-brasil-completa-30-anos) | 2022-06 | 2026-10-15 | média |
| 14 | Kits mistos: cada item segue sua regra | [Inmetro (FAQ)](https://www.gov.br/inmetro/pt-br/acesso-a-informacao/perguntas-frequentes/avaliacao-da-conformidade/artigos-escolares/quando-e-formado-um-kit-exemplo-brinquedo-e-artigo-escolar-vendidos-em-mesma-embalagem-como-proceder-com-a-certificacao) | s.d. | 2026-10-15 | alta |
| 15 | Edital exige selo Inmetro para kit de robótica | [Prefeitura de Joinville](https://www.joinville.sc.gov.br/public/edital/anexo/7a21dd092a85ea3a7b139b6895c75010.pdf) | s.d. | 2026-10-15 | média |
| 16 | LEGO SPIKE Prime por R$ 5.263 | [RoboCore](https://www.robocore.net/lego) | s.d. | 2026-10-15 | média |
| 17 | ACEBOTT ESP32 com 16 aulas por R$ 2.207 | [Casas Bahia](https://www.casasbahia.com.br/kit-acebott-iniciante-3em1-esp32-iot-fabrica-inteligente-para-programacao-e-educacao-steam-para-adolescentes/p/1582242008) | s.d. | 2026-10-15 | média |
| 18 | Portal DeepRacer Student encerrado | [AWS](https://aws.amazon.com/blogs/machine-learning/update-on-the-aws-deepracer-student-portal) | 2025 | 2026-10-15 | alta |
| 19 | Teachable Machine gratuito | [Google](https://blog.google/technology/ai/teachable-machine) | s.d. | 2026-10-15 | alta |
| 20 | IBM e Catavento: IA EDU gratuito | [DIO](https://www.dio.me/articles/ensinando-robos-exposicao-tem-o-objetivo-de-democratizar-o-conhecimento-sobre-inteligencia-artificial-no-brasil) | s.d. | 2026-10-15 | média |
| 21 | SIMROBÓTICA em Sorocaba | [Correio da Manhã](https://www.correiodamanha.com.br/nacional/sao-paulo/campinas/interior-de-sao-paulo/2026/01/amp/254591-empresa-cria-ia-para-robotica-educacional.html) | 2026-01 | 2026-10-15 | média |
| 22 | Curso gratuito de IA do MEC para professores | [Vestibulando Web](https://www.vestibulandoweb.com.br/cursos-gratuitos/curso-de-ia-para-professores-do-ensino-fundamental-e-lancado-pelo-mec/) | s.d. | 2026-10-15 | média |
| 23 | UFRN: 40.250 vagas gratuitas | [Revista Oeste](https://revistaoeste.com/oestegeral/2025/10/06/curso-da-ufrn-capacita-professores-para-inovar-com-inteligencia-artificial/) | 2025-10 | 2026-10-15 | média |
| 24 | Riscos da 18650; pilhas AA como alternativa | [DFRobot](https://wiki.dfrobot.com/mbt0050-18650/docs/22701) | s.d. | 2026-10-15 | alta |
| 25 | Células 18650 falsificadas e sem proteção | [CATEDU](https://libros.catedu.es/books/robotica-con-raspberry-y-python-alphabot/page/12-desventajas/export/pdf) | s.d. | 2026-10-15 | alta |
| 26 | RoboXperience: kit de baixo custo com impressão 3D | [SBC (Ideia)](https://sol.sbc.org.br/index.php/ideia/article/download/43457/43220/) | s.d. | 2026-10-15 | média |
| 27 | Q-learning com robô em sala de aula (em espanhol) | [CFR Ferrol](https://centros.edu.xunta.gal/cfrferrol/aulavirtual/mod/resource/view.php?id=22917) | s.d. | 2026-10-15 | média |
| 28 | Q-learning com LEGO NXT em menos de 100 iterações | [Universidade de Évora](https://dspace.uevora.pt/rdpc/handle/10174/12283) | s.d. | 2026-10-15 | média |
| 29 | Robótica escolar depende de formar o professor | [UFTM](https://seer.uftm.edu.br/revistaeletronica/index.php/revistatriangulo/article/download/505/pdf/6388) | s.d. | 2026-10-15 | média |
| 30 | Kits de desvio de obstáculos por regras, US$ 67 a 82 | [IHSG Online](https://www.ihsgonline.com/products/jsumo-prex-obstacle-avoidance-robot-kit/234964896/) | s.d. | 2026-10-15 | média |
| 31 | BNCC Computação sem habilidades de IA no Ensino Fundamental | [SBC (EduComp)](https://sol.sbc.org.br/index.php/educomp/article/download/34221/34012) | s.d. | 2026-10-15 | média |

## Quando reconferir

Os dados que envelhecem mais rápido são os preços de concorrentes [16][17][30], que valem por cerca de 3 meses: reconferir até **2027-01-15**. Os dados de compras públicas e da regulação [1][2][5][13] valem por cerca de 12 a 18 meses.
