# Requisitos do Sistema

## Requisitos Funcionais

### RF01 - Cadastro de Usuário
O sistema deve permitir que o usuário realize seu cadastro informando:

- Nome completo;
- E-mail válido;
- Senha com no mínimo 8 caracteres.

---

### RF02 - Login
O sistema deve autenticar o usuário por meio de e-mail e senha válidos.

---

### RF03 - Banco de Questões
O sistema deve disponibilizar questões organizadas por:

- Ano;
- Área;
- Tipo de questão (Formação Geral ou Formação Específica).

---

### RF04 - Simulados
O sistema deve permitir a realização de simulados contendo:

- Tempo cronometrado;
- Questões aleatórias.

---

### RF05 - Gabarito Comentado
O sistema deve apresentar a resposta correta juntamente com uma explicação detalhada da questão.

---

### RF06 - Estatísticas
O sistema deve apresentar ao usuário:

- Número de acertos;
- Número de erros;
- Tempo gasto na realização do simulado.

---

### RF07 - Fórum
Os usuários devem poder comentar e interagir nas questões disponíveis no sistema.

---

# Requisitos Não Funcionais

### RNF01 - Responsividade
O sistema deve ser responsivo e compatível com dispositivos desktop e mobile.

### RNF02 - Desempenho
O tempo de resposta do sistema deve ser inferior a 2 segundos.

### RNF03 - Segurança
O sistema deve possuir autenticação segura para acesso dos usuários.

### RNF04 - Disponibilidade
O sistema deve possuir disponibilidade mínima de 99%.

---

# Regras de Negócio

### RN01
Os simulados devem ser obrigatoriamente cronometrados.

### RN02
As questões devem ser organizadas por área de conhecimento.

### RN03
Apenas usuários autenticados poderão acessar os simulados.
