# **Especificações de Casos de Uso – Sistema de Apoio ao ENADE**

---

## **UC01 – Realizar Cadastro**

**Objetivo:** Permitir que um estudante se cadastre no sistema.

**Ator Principal:** Estudante

**Pré-condições:**

* O estudante não possuir cadastro ativo.

**Fluxo Principal:**

1. O estudante acessa a tela de cadastro.  
2. Informa seus dados pessoais.  
3. O sistema valida as informações.  
4. O sistema envia e-mail de validação.  
5. O estudante confirma o e-mail.  
6. O cadastro é concluído.

**Pós-condições:**

* Usuário cadastrado e apto a acessar o sistema.

---

## 

## **UC02 – Realizar Login**

**Objetivo:** Permitir acesso ao sistema.

**Ator Principal:** Estudante

**Pré-condições:**

* Usuário cadastrado.

**Fluxo Principal:**

1. O estudante informa e-mail e senha.  
2. O sistema autentica o usuário.  
3. O acesso é concedido.

**Fluxo Alternativo:**

* Credenciais inválidas.  
* O sistema exibe mensagem de erro.

---

## **UC03 – Acessar Dashboard**

**Objetivo:** Exibir informações gerais do usuário.

**Ator Principal:** Estudante

**Pré-condições:**

* Usuário autenticado.

**Fluxo Principal:**

1. O estudante acessa o dashboard.  
2. O sistema apresenta indicadores, simulados e desempenho.

---

## 

## 

## **UC04 – Realizar Simulado**

**Objetivo:** Permitir a realização de simulados preparatórios.

**Ator Principal:** Estudante

**Pré-condições:**

* Usuário autenticado.

**Fluxo Principal:**

1. O estudante seleciona um simulado.  
2. O sistema apresenta as questões.  
3. O estudante responde as questões.  
4. O sistema registra as respostas.  
5. O estudante finaliza o simulado.  
6. O sistema calcula o resultado.

**Pós-condições:**

* Resultado armazenado.

---

## **UC05 – Visualizar Resultados e Estatísticas**

**Objetivo:** Exibir desempenho do estudante.

**Ator Principal:** Estudante

**Pré-condições:**

* Existir ao menos um simulado realizado.

**Fluxo Principal:**

1. O estudante acessa a área de resultados.  
2. O sistema apresenta notas e estatísticas.  
3. O estudante pode visualizar desempenho por área.

---

## 

## **UC06 – Consultar Gabarito Comentado**

**Objetivo:** Permitir consulta das respostas corretas.

**Ator Principal:** Estudante

**Pré-condições:**

* Simulado finalizado.

**Fluxo Principal:**

1. O estudante seleciona um simulado concluído.  
2. O sistema apresenta o gabarito.  
3. O sistema exibe comentários e explicações das respostas.

---

## **UC07 – Gerenciar Questões (Professor)**

**Objetivo:** Permitir cadastro e manutenção de questões.

**Ator Principal:** Professor

**Fluxo Principal:**

1. O professor acessa o módulo de questões.  
2. Cadastra, altera ou remove questões.  
3. O sistema salva as alterações.

---

## **UC08 – Acompanhar Desempenho dos Alunos**

**Objetivo:** Monitorar resultados dos estudantes.

**Ator Principal:** Professor

**Fluxo Principal:**

1. O professor acessa a área de acompanhamento.  
2. Seleciona turma ou aluno.  
3. O sistema apresenta indicadores de desempenho.

---

## **UC09 – Emitir Relatórios**

**Objetivo:** Gerar relatórios acadêmicos.

**Ator Principal:** Coordenação Acadêmica

**Fluxo Principal:**

1. O usuário seleciona os filtros.  
2. Solicita a emissão do relatório.  
3. O sistema gera o documento.  
4. O relatório é exibido ou disponibilizado para download.

---

## **UC10 – Gerenciar Cursos e Turmas**

**Objetivo:** Manter informações acadêmicas.

**Ator Principal:** Coordenação Acadêmica

**Fluxo Principal:**

1. A coordenação acessa o módulo.  
2. Cadastra ou altera cursos.  
3. Cadastra ou altera turmas.  
4. O sistema salva as informações.

---

## **UC11 – Criar Tópico**

**Objetivo:** Criar discussões no fórum.

**Ator Principal:** Coordenação Acadêmica

**Fluxo Principal:**

1. O usuário acessa o fórum.  
2. Informa título e conteúdo.  
3. O sistema publica o tópico.

---

## **UC12 – Responder Tópico**

**Objetivo:** Participar das discussões do fórum.

**Ator Principal:** Coordenação Acadêmica

**Fluxo Principal:**

1. O usuário seleciona um tópico.  
2. Digita sua resposta.  
3. O sistema publica a mensagem.

---

## **UC13 – Gerenciar Usuários**

**Objetivo:** Administrar usuários do sistema.

**Ator Principal:** Administrador

**Fluxo Principal:**

1. O administrador acessa o módulo de usuários.  
2. Consulta usuários cadastrados.  
3. Realiza inclusão, edição, bloqueio ou exclusão.  
4. O sistema registra as alterações.

---

## **UC14 – Gerenciar Questões (Administrador)**

**Objetivo:** Administrar o banco de questões.

**Ator Principal:** Administrador

**Fluxo Principal:**

1. O administrador acessa o módulo.  
2. Cadastra, altera ou remove questões.  
3. O sistema salva as alterações.

---

## **UC15 – Gerenciar Simulados**

**Objetivo:** Criar e administrar simulados.

**Ator Principal:** Administrador

**Fluxo Principal:**

1. O administrador cria um simulado.  
2. Seleciona as questões.  
3. Define critérios e configurações.  
4. O sistema publica o simulado.

---

## **UC16 – Gerenciar Conteúdos**

**Objetivo:** Administrar materiais de estudo.

**Ator Principal:** Administrador

**Fluxo Principal:**

1. O administrador acessa o módulo.  
2. Adiciona, altera ou remove conteúdos.  
3. O sistema salva as informações.

---

## **UC17 – Gerenciar Fórum**

**Objetivo:** Administrar as discussões do sistema.

**Ator Principal:** Administrador

**Fluxo Principal:**

1. O administrador acessa o fórum.  
2. Modera tópicos e respostas.  
3. Remove conteúdos inadequados quando necessário.  
4. O sistema registra as ações.

---

## **UC18 – Validar E-mail**

**Objetivo:** Confirmar autenticidade do endereço eletrônico informado.

**Ator Principal:** Sistema / Serviço de E-mail

**Fluxo Principal:**

1. O sistema envia um e-mail de validação.  
2. O usuário acessa o link recebido.  
3. O sistema confirma o endereço.  
4. O cadastro é validado.

---

## **UC19 – Autenticar Usuário**

**Objetivo:** Validar credenciais de acesso.

**Ator Principal:** Sistema

**Fluxo Principal:**

1. O sistema recebe login e senha.  
2. Verifica as credenciais.  
3. Libera ou bloqueia o acesso conforme resultado da validação.

---

## **UC20 – Finalizar Simulado**

**Objetivo:** Encerrar oficialmente a realização do simulado.

**Ator Principal:** Estudante

**Fluxo Principal:**

1. O estudante seleciona a opção de finalizar.  
2. O sistema confirma a ação.  
3. O sistema calcula a pontuação.  
4. O resultado é armazenado e disponibilizado para consulta.

