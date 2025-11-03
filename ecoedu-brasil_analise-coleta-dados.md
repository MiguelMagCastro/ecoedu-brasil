# 📊 Análise da Coleta de Dados — EcoEdu Brasil

## 🎯 Objetivo
A etapa de coleta de dados teve como propósito compreender o nível de conhecimento, dificuldades e preferências dos potenciais usuários do **EcoEdu Brasil**, para subsidiar o design do sistema educativo voltado à conscientização sobre queimadas e educação ambiental.

---

## 👥 Perfil dos Participantes
Foram coletadas respostas de **8 participantes**, distribuídos entre:
- **4 estudantes** (ensino fundamental e médio);
- **2 professores de ciências/biologia**;
- **2 pais/responsáveis** (moradores de áreas próximas a regiões afetadas por queimadas).

Faixa etária predominante: **10 a 38 anos**.  
Todos declararam possuir **acesso à internet**, sendo o **celular** o meio mais utilizado para acessar conteúdos educativos.

---

## 📚 1. Nível de conhecimento e percepção sobre queimadas
- **75%** dos participantes declararam entender *regular* ou *bem* o que causa queimadas.  
- **100%** consideram o tema “queimadas e desmatamento” *muito importante* para a comunidade.  
- Apenas **37,5%** já participaram de atividades escolares ou comunitárias sobre o tema.

🟢 **Interpretação:** o tema é amplamente reconhecido como importante, mas as oportunidades de aprendizado prático ainda são escassas.  
🔸 *Implica necessidade de promover atividades interativas e educativas contínuas.*

---

## 💬 2. Tipos de informação mais valorizados
Classificação média dos tipos de conteúdo (1 = mais importante, 6 = menos importante):

| Tipo de informação | Média de importância | Interpretação |
|--------------------|----------------------|----------------|
| O que são queimadas e causas | **1,8** | Grande interesse em compreender o fenômeno. |
| Impactos na saúde humana | **2,4** | Alta preocupação com efeitos diretos. |
| Impactos na fauna e flora | **2,6** | Tema relevante para conscientização geral. |
| Como prevenir / boas práticas locais | **1,9** | Forte interesse em soluções e ações práticas. |
| Notícias e mapas de focos atuais | **3,8** | Interesse moderado. |
| Atividades e materiais para escolas | **2,1** | Prioridade para professores e alunos. |

🟢 **Síntese:** o público quer aprender **como prevenir** e **entender causas** de queimadas, de forma prática e didática.

---

## 🚧 3. Dificuldades de acesso e aprendizado
As principais dificuldades mencionadas foram:
- Linguagem muito técnica (6/8 respostas);  
- Falta de material adaptado para crianças (5/8);  
- Conteúdos longos e pouco atrativos (4/8);  
- Dificuldade de acesso à internet em algumas escolas públicas (2/8).

🔸 **Conclusão:** há necessidade de uma plataforma com linguagem simples, conteúdo leve e recursos acessíveis offline (ou com baixo consumo de dados).

---

## 🎮 4. Preferências de aprendizado e formato
Formas de aprendizado mais citadas:
- **Vídeos curtos (2–5 min)** — 6 menções;  
- **Jogos e quizzes interativos** — 5 menções;  
- **Infográficos e imagens** — 4 menções.

Além disso:
- **87%** acharam muito útil ter *quizzes* e desafios ao final dos módulos.  
- **75%** gostariam de ver *pontuação e recompensas* (gamificação).  
- **62%** sugeriram *certificados ou desafios práticos em escolas*.

🟢 **Síntese:** o público deseja uma **experiência lúdica, interativa e visual**, em vez de leituras longas.

---

## 🌍 5. Acessibilidade e usabilidade
- Todos os participantes apoiaram o uso de **linguagem simples e acessível**.  
- 50% destacaram a importância de **legendas em vídeos**.  
- Um participante mencionou a necessidade de **leitor de tela** para alunos com deficiência visual.

🔸 **Implicação:** o sistema deve seguir diretrizes básicas de acessibilidade digital (WCAG), incluindo legendas, contraste adequado e compatibilidade com leitores de tela.

---

## 💡 6. Principais insights qualitativos
Analisando as respostas abertas e comentários finais, destacam-se os seguintes pontos:
- **“As aulas sobre queimadas são muito teóricas, e às vezes cansam.”**  
- **“Seria bom um jogo onde a gente aprendesse brincando.”**  
- **“Os professores precisam de materiais prontos, fáceis de aplicar.”**  
- **“A internet da escola é ruim, então o site deve funcionar mesmo com pouca conexão.”**

🧩 **Síntese geral:**  
O público demonstra **interesse e disposição para aprender**, mas precisa de uma solução **simples, leve, divertida e educativa**. O sistema deve unir **conteúdo informativo, interatividade e gamificação**.

---

## 🧱 7. Derivação de Requisitos

### ✅ Requisitos Funcionais (RF)
| ID | Requisito | Origem / Justificativa |
|----|------------|------------------------|
| **RF-01** | O sistema deve permitir que os usuários realizem quizzes e desafios ao final de cada módulo. | Preferência expressa por 87% dos participantes. |
| **RF-02** | O site deve oferecer vídeos educativos curtos (2–5 minutos) sobre queimadas e meio ambiente. | 6 menções diretas. |
| **RF-03** | O sistema deve incluir área para professores aplicarem atividades e acompanharem o progresso dos alunos. | Reforçado pelos docentes entrevistados. |
| **RF-04** | O sistema deve gerar certificados ou medalhas digitais após a conclusão de atividades. | 62% sugeriram recompensas. |
| **RF-05** | O sistema deve ter conteúdo dividido em módulos temáticos (Causas, Prevenção, Impactos, etc.). | Clareza e organização do conteúdo. |
| **RF-06** | O sistema deve permitir comentários ou compartilhamento de ideias sobre práticas sustentáveis. | Desejo de engajamento e troca. |

---

### ⚙️ Requisitos Não Funcionais (RNF)
| ID | Requisito | Origem / Justificativa |
|----|------------|------------------------|
| **RNF-01** | Linguagem simples e acessível, adequada a estudantes do ensino fundamental. | 6 menções à dificuldade com linguagem técnica. |
| **RNF-02** | Compatibilidade com dispositivos móveis (celulares e tablets). | 100% dos acessos declarados via celular. |
| **RNF-03** | Sistema otimizado para baixo consumo de dados e funcionamento parcial offline. | 2 menções a conexão limitada. |
| **RNF-04** | Todos os vídeos devem conter legendas e transcrições. | 50% dos participantes solicitaram legendas. |
| **RNF-05** | Interface intuitiva, com navegação por ícones e cores contrastantes. | Preferência por design lúdico e inclusivo. |
| **RNF-06** | A plataforma deve estar em conformidade com diretrizes WCAG 2.1 (acessibilidade digital). | Inclusão e acessibilidade. |

---

## 🧭 8. Conclusão
A coleta de dados revelou um público **altamente receptivo**, mas que **carece de ferramentas educativas acessíveis e engajantes**.  
O **EcoEdu Brasil** deve, portanto, priorizar:
- **Linguagem clara e visual**, voltada a crianças e adolescentes;  
- **Aprendizado ativo**, por meio de quizzes, vídeos e jogos curtos;  
- **Recursos para professores**, facilitando o uso pedagógico em sala;  
- **Acessibilidade e leveza técnica**, garantindo acesso mesmo com limitações de internet.

