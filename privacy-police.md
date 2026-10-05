# POLÍTICA DE PRIVACIDADE DO APLICATIVO MENTISAI

**Última atualização:** 05 de outubro de 2026

O **MentisAI** ("nós", "nosso" ou "aplicativo") tem o compromisso de proteger a privacidade e os dados pessoais de seus usuários. Esta Política de Privacidade descreve como coletamos, usamos, armazenamos e tratamos suas informações pessoais e biométricas ao utilizar o aplicativo móvel e a infraestrutura do ecossistema MentisAI.

Ao utilizar o MentisAI, você concorda com a coleta e o uso de informações de acordo com esta política.

---

### 1. INFORMAÇÕES QUE COLETAMOS

Para oferecer as funcionalidades de acompanhamento e triagem de sintomas depressivos, o MentisAI coleta e processa os seguintes tipos de dados:

#### A. Dados de Identificação e Conta

* **Informações de Login:** Nome, endereço de e-mail e foto de perfil obtidos via autenticação unificada do Google (*Single Sign-On*).

#### B. Dados de Saúde e Biométricos (via Health Connect)

Com a autorização explícita do usuário, o aplicativo acessa dados passivos de saúde sincronizados pelo *middleware* **Health Connect** no sistema operacional Android, incluindo:

* **Frequência Cardíaca:** Leituras de batimentos por minuto (bpm) e séries temporais.
* **Análise do Sono:** Duração do sono, horários de início/fim e estágios de sono.
* **Atividade Física:** Contagem diária de passos e estimativa de gasto calórico (kcal).

#### C. Dados Armazenados Localmente

* Prefirações do aplicativo e dados de cadastro armazenados de forma segura e criptografada no banco de dados local do seu dispositivo (**SQLite**).

---

### 2. COMO UTILIZAMOS SUAS INFORMAÇÕES

Os dados coletados são utilizados exclusivamente para as seguintes finalidades:

* **Processamento e Visualização:** Exibir gráficos diários e semanais de evolução da saúde e hábitos físicos do próprio usuário no painel do aplicativo.
* **Estratificação de Risco e Triagem:** Alimentar modelos de Inteligência Artificial e aprendizado de máquina para identificar padrões e gerar relatórios automatizados de bem-estar (*MentisAI Insight*).
* **Melhoria Contínua:** Validar a precisão dos algoritmos de triagem cognitiva.

---

### 3. COMPARTILHAMENTO E PRIVACIDADE DE DADOS DE SAÚDE

* **Não Vendemos seus Dados:** O MentisAI **não vende, aluga ou comercializa** dados pessoais ou biométricos a terceiros sob nenhuma hipótese.
* **Não Uso Comercial/Publicitário:** Seus dados de saúde obtidos via Health Connect **nunca** serão utilizados para fins publicitários, comercialização de anúncios ou perfilamento para marketing.
* **Comunicação Segura:** As requisições enviadas ao servidor em nuvem (*backend*) para processamento de inferências ocorrem por canais seguros, utilizando criptografia estrita via protocolo **HTTPS/TLS**.

---

### 4. ARMAZENAMENTO E SEGURANÇA DOS DADOS

* **Computação de Borda (*Edge Computing*):** A persistência primária de preferências e histórico de utilização é mantida localmente no próprio smartphone do usuário via **SQLite**.
* **Criptografia:** Toda a comunicação entre o aplicativo e a API em nuvem (FastAPI/Docker) utiliza criptografia de ponta a ponta em trânsito (HTTPS).
* **Retenção de Dados:** Mantemos seus dados apenas pelo tempo necessário para cumprir os propósitos descritos nesta política ou conforme exigido por regulamentações legais aplicáveis.

---

### 5. ISENÇÃO DE RESPONSABILIDADE MÉDICA (*MEDICAL DISCLAIMER*)

O **MentisAI é uma ferramenta de suporte, conscientização e triagem preventiva**, desenvolvida para fins informativos e acadêmicos.

**O MENTISAI NÃO CONSTITUI DIAGNÓSTICO MÉDICO OU PSIQUIÁTRICO OFICIAL E NÃO SUBSTITUI O ACOMPANHAMENTO POR PROFISSIONAIS DE SAÚDE MENTAL QUALIFICADOS (PSICÓLOGOS E PSIQUIATRAS).** 

---

### 6. SEUS DIREITOS (LGPD)

Em conformidade com a Lei Geral de Proteção de Dados (LGPD), você possui o direito de:

* **Acessar e Confirmar:** Verificar quais dados pessoais e biométricos estão sendo processados.
* **Revogar Permissões:** Revogar a qualquer momento a autorização de leitura de dados de saúde diretamente nas configurações do seu sistema Android (*Configurações > Health Connect*).
* **Exclusão de Conta e Dados:** Solicitar a exclusão definitiva dos seus dados cadastrais e histórico de processamento entrando em contato com a nossa equipe de suporte.

---

### 7. CONTATO E SUPORTE

Se você tiver dúvidas, sugestões ou solicitações referentes a esta Política de Privacidade ou ao tratamento de seus dados, entre em contato através do e-mail:

* **E-mail de Suporte:** `willianjfurtado19@gmail.com` 
* **Instituição Vinculada:** Instituto Federal de Educação, Ciência e Tecnologia do Maranhão (IFMA) – Campus Caxias.
