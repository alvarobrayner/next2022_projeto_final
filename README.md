# Programa
- Extrator de Imagens em Documentos .XLSX

# Descrição
Com o propósito de realizar o processamento de informações em documentos, existe a necessidade de realizar extração de imagens em documentos .XLSX com um objetivo futuro de utilizar essas imagens para processamentos que ajudarão na tomada de decisão em auditorias.

# Objetivo
Implementar uma API que fornece operações necessárias para:

- Realizar o processamento de um documento do tipo .XLSX, extrair as imagens desse documento e armazená-las em uma base de dados e/ou sistema de arquivos;
- Recuperar a lista de todos os documentos processados, considerando a paginação de dados para evitar lentidão na consulta e na recuperação das informações;
- Recuperar um documento específico através de um identificador do documento, que foi gerado dinamicamente na hora do seu processamento;
- Recuperar uma imagem extraída através de um identificador da imagem, que foi gerado quando a imagem foi extraída do documento;
- Remover da lista de documentos processados um documento específico e todas as suas imagens através do identificador do documento.

Validações para as operações deverão ser consideradas na implementação do serviço e deverá retornar uma identificação do problema ocorrido. Validações necessárias: 

- Validar se o tipo do documento é válido (apenas .XLSX será aceito);
- Validar se o arquivo não está corrompido;
- Processar apenas documentos com ao menos uma imagem.

## Referências
- http://poi.apache.org/components/spreadsheet/quick-guide.html 
- https://spring.io/guides/tutorials/rest/ 
- https://github.com/cthackers/adm-zip 
- https://flask.palletsprojects.com

# Criado por
- Alaíde Lima
[GitHub](https://github.com/AlaideLima) <div>
[LinkedIn](https://www.linkedin.com/in/alaide-lima-706b51200/)
- Álvaro Brayner
[GitHub](https://github.com/alvarobrayner) <div>
[LinkedIn](https://www.linkedin.com/in/alvarobrayner/)
- Ana Azevedo
[GitHub](https://github.com/anaazevedoferreira) <div>
[LinkedIn](https://www.linkedin.com/in/ana-azevedo-arquiteta/)

Mentoria:
- Antônio Júnior
- Gabriel Calazans

Trabalho de conclusão do curso NExT - Nova Experiência de Trabalho, da CESAR School.