# Desafio técnico de integração de sistemas



O objetivo deste desafio é avaliar seu domínio sobre conceitos e técnicas de Integração de Sistemas.



**Lembrando!**  Este é um teste para todos os níveis, portanto, não esperamos que você conclua 100% ou utilize todos os conceitos citados. Queremos saber sobre seu conhecimento e a forma como você trabalha.



## Primeira etapa do desafio: Seguindo um tutorial.



- Para dar início ao seu teste técnico você precisará do Pentaho PDI versão 8.0, faça download aqui na [página oficial do projeto](https://sourceforge.net/projects/pentaho/files/Pentaho%208.0/client-tools/pdi-ce-8.0.0.0-28.zip/download).



- Em seguida, pedimos que você desenvolva um projeto em Pentaho PDI acessando um Web Service SOAP dos correios para extrair a data estimada da entrega de postagens.



- Siga [este tutorial](http://www.matera.com/blog/post/acessando-web-services-com-pentaho-di) para concluir a etapa.



Note que no tutorial do link a saída de dados utilizada foi o step `"Microsoft Excel Output"`, mas você *deverá* substituir este pelo step `"Write to log"` e imprimir o resultado no console.



## Segunda etapa do desafio: Criando a solução.



- Agora, você irá desenvolver um projeto em Pentaho PDI acessando Web Service REST para consulta de endereços utilizando um CEP.



- Acesse o link [ViaCep](https://viacep.com.br/) e utilize o Web Service fornecido pela página para criar uma transformação.



### Dicas

- Inicie com o step `"Generate Rows"` para informar o CEP desejado.

- Para a extração do JSON de retorno, utilize o step `"Json Input"`.

- Faça o print no console das informações do endereço com o step `"Write to log"`.



### A apresentação do desafio

- Crie um repositório para o projeto em sua conta pessoal no GitHub;

- Nos envie o link do repositório via Plataforma GUPY por onde recebeu essas instruções.
