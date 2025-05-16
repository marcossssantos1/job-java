📄 job-java
O job-java é um projeto desenvolvido em Java, utilizando o framework Spring Batch, com o objetivo de processar dados de forma eficiente e escalável. Este projeto serve como base para a criação de jobs batch que podem ser integrados em sistemas maiores ou utilizados para tarefas específicas de processamento em lote.

🚀 Tecnologias Utilizadas
Java 21

Spring Boot 3.4.5

Spring Batch

Maven
GitHub
+2
GitHub
+2
GitHub
+2

🧱 Estrutura do Projeto
O projeto está organizado da seguinte forma:

src/main/java: Contém o código-fonte principal da aplicação.

src/main/resources: Arquivos de configuração e recursos utilizados pela aplicação.

pom.xml: Arquivo de configuração do Maven, gerenciando as dependências do projeto.

⚙️ Configuração e Execução
Pré-requisitos
Java 21 instalado e configurado.

Maven instalado.

Passos para Execução
Clone o repositório:
GitHub

bash
Copiar
Editar
git clone https://github.com/marcossssantos1/job-java.git
cd job-java
Compile o projeto:

bash
Copiar
Editar
mvn clean install
Execute a aplicação:

bash
Copiar
Editar
mvn spring-boot:run
🛠️ Configuração do IntelliJ IDEA
Para garantir que o projeto funcione corretamente no IntelliJ IDEA:

Abra o projeto no IntelliJ IDEA.

Vá em File > Project Structure > Project.

Em Project SDK, selecione o JDK 21.

Em Project language level, selecione 21 - (Java 21).

Certifique-se de que o Maven está configurado corretamente em Build, Execution, Deployment > Build Tools > Maven.
