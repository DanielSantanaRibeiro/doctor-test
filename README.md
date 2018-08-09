Desafio Java - Doctor Test
A proposta do desafio é a criação de uma API RESTful, para gerir a agenda de um consultório
médico.
- Cadastro de Médicos (Nome, CRM, Idade).
- Consultório (Número)
- Cadastro das consultas médicas
- Consultas das consultas médicas cadastradas
Cada marcação de consulta deve conter obrigatoriamente as seguintes informações:
- Nome do Paciente
- Especialidade Médica
- Nome do Médico
- CRM do Médico
- Data/Hora
- Nº Consultório
As seguintes regras devem ser respeitadas no fluxo de cadastro das consultas médicas:
- O intervalo das consultas no mesmo consultório, deve respeitar um tempo mínimo de 15
minutos.
- O mesmo paciente não pode marcar duas consultas no mesmo dia.
- Um médico deve atender todas as consultas do dia, no mesmo consultório.
- Para evitar problemas, as consultas devem se limitar a no máximo 12 por dia num mesmo
consultório
- O fluxo de cadastro deve permitir que se forneça o mesmo consultório, para 2 médicos
diferentes, apenas se a consulta for da especialidade "Cirurgião". Para as demais consultas,
não se deve permitir a utilização do consultório por dois médicos, no mesmo horário
- Para situações de erro, é necessário que a resposta da requisição seja coerente em exibir
uma mensagem condizente com o erro.
O endpoint de consulta deve retornar os resultados ordenados por Data/Hora da Consulta e deve
permitir filtrar todas consultas para uma data e todas as consultas para um determinado médico.
Esse filtro não é obrigatório - se não for fornecido todas as consultas devem ser retornadas.
Pontos relevantes
- Utilize a plataforma Java para o desenvolvimento da solução do desafio
- Desejável a utilizar de Angular JS como framework de front-end. Caso não haja
conhecimento em Angular, outro framework pode ser utilizado.
- Fique a vontade para utilização de outras bibliotecas no projeto
- Desejável a utilização de Spring Boot ou Hibernate para persistência, mas fique a vontade
para utilização de qualquer outro método. Uma sugestão é a utilização de banco de dados
em memória, como HSQLDB
- Entende que testes unitários são necessários para garantia da qualidade do código
entregue? Se sim, seria interessante escrever os testes unitários
- Para enviar o código do desafio, utilize sua conta pessoal do Github ou
Bitbucket, e nos envie o endereço do repositório (o repositório deve ser público).
Observe o prazo que lhe foi passado para realizar essa entrega.Desafio Java - Logus Retail
A proposta do desafio é a criação de uma API RESTful, para gerir a agenda de um consultório
médico.
- Cadastro de Médicos (Nome, CRM, Idade).
- Consultório (Número)
- Cadastro das consultas médicas
- Consultas das consultas médicas cadastradas
Cada marcação de consulta deve conter obrigatoriamente as seguintes informações:
- Nome do Paciente
- Especialidade Médica
- Nome do Médico
- CRM do Médico
- Data/Hora
- Nº Consultório
As seguintes regras devem ser respeitadas no fluxo de cadastro das consultas médicas:
- O intervalo das consultas no mesmo consultório, deve respeitar um tempo mínimo de 15
minutos.
- O mesmo paciente não pode marcar duas consultas no mesmo dia.
- Um médico deve atender todas as consultas do dia, no mesmo consultório.
- Para evitar problemas, as consultas devem se limitar a no máximo 12 por dia num mesmo
consultório
- O fluxo de cadastro deve permitir que se forneça o mesmo consultório, para 2 médicos
diferentes, apenas se a consulta for da especialidade "Cirurgião". Para as demais consultas,
não se deve permitir a utilização do consultório por dois médicos, no mesmo horário
- Para situações de erro, é necessário que a resposta da requisição seja coerente em exibir
uma mensagem condizente com o erro.
O endpoint de consulta deve retornar os resultados ordenados por Data/Hora da Consulta e deve
permitir filtrar todas consultas para uma data e todas as consultas para um determinado médico.
Esse filtro não é obrigatório - se não for fornecido todas as consultas devem ser retornadas.
Pontos relevantes
- Utilize a plataforma Java para o desenvolvimento da solução do desafio
- Desejável a utilizar de Angular como framework de front-end. Caso não haja
conhecimento em Angular, outro framework pode ser utilizado.
- Fique a vontade para utilização de outras bibliotecas no projeto
- Desejável a utilização de Spring Boot ou Hibernate para persistência, mas fique a vontade
para utilização de qualquer outro método. Uma sugestão é a utilização de banco de dados
em memória, como HSQLDB
- Entende que testes unitários são necessários para garantia da qualidade do código
entregue? Se sim, seria interessante escrever os testes unitários
- Para enviar o código do desafio, faça um fork desse repositorio e nos envie uma solicitação de Pull Request