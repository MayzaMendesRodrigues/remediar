# 💊 REMEDIAR
### Doação Inteligente de Medicamentos
*Documentação completa do projeto · Clube da programacao · Laura Debugras · Junho 2026*
www.remediar.org


---

## 1. Descrição do Projeto

> **O Remediar transforma o remédio esquecido na sua prateleira em tratamento para quem não pode comprar.**

Aplicativo mobile que conecta pessoas com medicamentos válidos sobrando a pacientes carentes que precisam deles. Com triagem farmacêutica responsável, rastreabilidade legal e dados para gestão pública, o Remediar transforma desperdício em acesso à saúde.

---

## 2. Qual problema resolve

### Três problemas ao mesmo tempo

**Para quem doa**
Não sabe o que fazer com medicamentos válidos sobrando — e acaba jogando fora algo que custou dinheiro e poderia ajudar alguém.

**Para quem precisa**
Interrompe tratamentos essenciais por falta de acesso financeiro — não é falta de remédio no mundo, é falta de acesso a ele.

**Para o meio ambiente**
Medicamentos descartados no lixo ou no esgoto contaminam rios e aquíferos que nenhuma estação de tratamento convencional consegue limpar.

> 💡 O Remediar resolve os três com uma única ação — o cadastro do medicamento.

### O contexto humano

Em algum momento da vida, quase todo mundo já abriu o armário de casa e encontrou uma caixinha de remédio pela metade. O tratamento acabou antes. O médico trocou a medicação. Um familiar não precisou mais. E aquele medicamento válido, que custou dinheiro, simplesmente ficou lá — até ir para o lixo.

Do outro lado dessa história, existe uma mãe que interrompeu o tratamento da pressão porque não tinha dinheiro para comprar o remédio naquele mês. Um idoso que escolheu entre a medicação e a conta de luz. Uma criança que ficou sem antibiótico porque a UBS estava em falta.

> *"Essas duas histórias acontecem ao mesmo tempo, no mesmo bairro, às vezes no mesmo prédio. E nunca se encontram — até agora."*

---

## 3. Usuários e clientes ideais

São quatro perfis, cada um com um papel diferente na plataforma:

### 🟢 Quem doa
Pessoa comum, qualquer classe social, que tem medicamentos válidos sobrando em casa — tratamento que mudou, caixa que sobrou, remédio que o médico trocou. Quer descartar com responsabilidade mas não sabe como.

### 🔴 Quem recebe
Pessoa de baixa renda com doença crônica ou aguda que não consegue comprar o medicamento naquele mês. Também ONGs, orfanatos e asilos que dependem de doações para garantir medicamentos básicos para quem cuidam.

- Famílias de baixa renda com doenças crônicas
- ONGs e abrigos que atendem crianças e adultos em vulnerabilidade
- Asilos e casas de repouso que precisam de medicação contínua

### 🔵 Farmacêutico parceiro
Profissional registrado no CRF que quer ter um papel ativo no acesso à saúde da sua comunidade — e que vê na parceria visibilidade, dados e impacto social sem custo extra. É o elo que viabiliza o projeto.

### 🟣 Gestor público e ONGs
Organizações que precisam de dados reais sobre demanda de medicamentos por região para tomar decisões de política pública — e que hoje não têm essa informação de forma organizada.

> ⚠️ **O cliente que viabiliza o projeto é o farmacêutico parceiro. Sem ele, nada chega a ninguém.**

---

## 4. Dados estatísticos

- **66% a 78%** dos brasileiros descartam medicamentos válidos no lixo residencial
- **10% a 20%** descartam medicamentos diretamente no esgoto — toaletes ou pias — contaminando rios e aquíferos
- **~64%** de estoque não utilizado em áreas com alta taxa de automedicação

### Contexto regional

**🇨🇴 Colômbia**
Pioneira com a Resolução nº 371 — obriga farmacêuticas a criar programas nacionais de recolhimento de medicamentos vencidos ou não utilizados.

**🇧🇷 Brasil**
Descarte pelo consumidor ainda negligenciado pela legislação federal, mas estados avançam com normas de logística reversa que exigem farmácias como pontos de coleta, como a Farmácia do Povo.

**🇨🇱 Chile e região**
Mais de 96% da população desconhece pontos de coleta designados — dependendo quase exclusivamente de campanhas municipais e iniciativas educativas.

---

## 5. Funcionalidades construídas

O fluxo completo do app já existe e está funcional. Os dados exibidos hoje são mockados porque, para o app entrar em produção real, precisamos de farmácias parceiras cadastradas.

Pensando nisso, criamos uma landing page para validar o interesse do mercado antes de escalar — essa é a estratégia do MVP: não construir mais tecnologia antes de confirmar que as farmácias querem participar.

### ✅ O que já está construído

- Fluxo do doador — cadastro de medicamento com foto e validade
- Painel de triagem farmacêutica — aprovação e reprovação com rastreabilidade
- Fluxo do paciente — busca por farmácia parceira no mapa e retirada
- Landing page de captação de farmácias parceiras

### ⏳ O que depende das farmácias para ativar

- Dados reais de medicamentos disponíveis
- Geolocalização de pontos de retirada
- Dispensação supervisionada de verdade

---

## 6. Validação do projeto

O projeto foi validado com familiares, amigos da área da saúde, membros do grupo do Clube da Programação e feedback da comunidade. Os perfis incluíram médicos, estudantes de saúde, pessoas que trabalham em ONGs e farmacêuticos — todos confirmando que o Remediar resolve um problema real e que participariam da plataforma.

### Perguntas feitas nas entrevistas

As perguntas iniciais foram:

- Se o SUS supre a necessidade das comunidades e pessoas que precisam de medicamentos
- Se no Paraguai existe assistência para os mais necessitados e se distribuem medicamentos como o SUS faz no Brasil

### O que mudou depois do Mom Test

No segundo encontro do Clube da Programação, o tema foi o **Mom Test** — e percebemos que nossas perguntas iniciais tinham um problema clássico: eram perguntas de opinião e contexto, não perguntas que revelam comportamento real. Qualquer pessoa que trabalha com vulnerabilidade social vai confirmar que o sistema não supre. Estávamos validando o que já sabíamos, não aprendendo nada novo.

As perguntas que passamos a fazer:

- *"Me conta a última vez que faltou um medicamento para alguém que você atende. O que aconteceu?"*
- *"Como você resolve hoje quando falta remédio?"*
- *"Você já recebeu ou doou medicamento antes? Como foi?"*
- *"O que te impediria de usar uma plataforma como essa?"*

> 💡 Perguntas que revelam comportamento real — não intenção, não opinião.

---

## 7. Feedback que decidimos não incorporar

### A decisão de não lançar o app antes de ter farmácias parceiras

O feedback que recebemos confirmou que o projeto é viável e necessário. A tentação natural seria lançar o app com dados reais e esperar que as farmácias entrassem por conta própria.

Decidimos não fazer isso porque sem uma farmácia parceira, o app não funciona na prática. O medicamento doado não tem para onde ir. A triagem não acontece. O paciente não retira nada.

Em vez disso, priorizamos a landing page como primeiro passo — validar o interesse das farmácias antes de escalar a tecnologia.

> *"O MVP não é o app completo, é a confirmação de que o elo mais crítico do fluxo quer participar."*

O feedback que **não** incorporamos foi: *"já lança e vê o que acontece."* Porque lançar sem farmácia parceira seria construir uma ponte que começa no meio — bonita, mas que não leva a lugar nenhum.

---



*Remediar — Desafio de Inovação em Saúde — Junho 2026*
