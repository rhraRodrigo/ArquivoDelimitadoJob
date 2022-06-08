# ArquivoDelimitadoJob
Spring Batch - Leitura de arquivos com campos delimitados por vírgula.

Leitura de arquivo com largura fixa em Spring Batch

#Pt-BR

Informações para que o projeto consiga ser rodado:

Configurar sua conexão MySQL no arquivo application.properties

- Configurar o caminho do arquivo de teste na classe "LeituraArquivoDelimitadoReaderConfig", método "leituraArquivoDelimitadoReader". 
- Definir o parâmetro do job 'arquivoClientes' em Run > Run Configurations > Spring boot application > Arguments > Program Arguments:

arquivoClientes=file:files/clientes.txt

# En-US

Instructions to compile your project:

Configure your MySQL connection properties in application.properties

- Configure location test file in class "LeituraArquivoDelimitadoReaderConfig", method "leituraArquivoDelimitadoReader". 
- Define job parameter 'arquivoClientes' on Run > Run Configurations > Spring boot application > Arguments > Program Arguments:

arquivoClientes=file:files/clientes.txt
