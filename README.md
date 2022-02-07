# Intro-WebRestful

Um serviço que aceitará solicitações HTTP GET em http://localhost:8080/greeting.

Ele responderá com uma representação JSON de uma saudação, como mostra a listagem a seguir:

{"id":1,"content":"Hello, World!"}

Você pode personalizar a saudação com um parâmetro opcional namena string de consulta, como mostra a lista a seguir:

http://localhost:8080/greeting?name=User
O namevalor do parâmetro substitui o valor padrão de Worlde é refletido na resposta, como mostra a listagem a seguir:

{"id":1,"content":"Hello, User!"}