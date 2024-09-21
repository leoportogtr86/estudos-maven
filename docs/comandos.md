# 50 Comandos Mais Usados na CLI do Maven

| Comando Maven           | Descrição                                                     | Objetivo                                                         |
|-------------------------|---------------------------------------------------------------|------------------------------------------------------------------|
| `mvn clean`             | Limpa os arquivos gerados pelo build anterior.                | Manter o diretório limpo para novas compilações.                  |
| `mvn compile`           | Compila o código fonte do projeto.                            | Transformar o código-fonte em bytecode.                           |
| `mvn test`              | Executa os testes unitários.                                  | Garantir que o código funcione conforme esperado.                 |
| `mvn package`           | Empacota o código compilado em um JAR ou WAR.                 | Criar o pacote final para distribuição.                           |
| `mvn install`           | Instala o pacote no repositório local.                        | Tornar o artefato disponível para outros projetos localmente.     |
| `mvn deploy`            | Faz o deploy do artefato em um repositório remoto.            | Publicar o artefato para repositórios remotos.                    |
| `mvn validate`          | Valida se o projeto está correto e todas as dependências estão presentes. | Verificar se o projeto pode prosseguir no ciclo de build.         |
| `mvn site`              | Gera o site do projeto com documentação e relatórios.         | Criar documentação e relatórios automáticos.                      |
| `mvn test-compile`      | Compila as classes de teste.                                  | Compilar as classes usadas nos testes.                            |
| `mvn verify`            | Verifica se o projeto está pronto para o deploy, executando testes de integração. | Validar o build final antes de publicar.                         |
| `mvn clean install`     | Limpa e instala o projeto no repositório local.               | Preparar o projeto para uso local.                                |
| `mvn clean deploy`      | Limpa e faz o deploy do projeto no repositório remoto.        | Fazer o deploy para repositórios de produção.                     |
| `mvn dependency:tree`   | Mostra a árvore de dependências do projeto.                   | Analisar dependências e seus conflitos.                           |
| `mvn dependency:list`   | Lista todas as dependências do projeto.                       | Ter uma visão completa das bibliotecas usadas.                    |
| `mvn dependency:resolve`| Resolve e baixa todas as dependências do projeto.             | Baixar dependências necessárias para o projeto.                   |
| `mvn versions:display-dependency-updates` | Mostra as atualizações de dependências disponíveis. | Manter as dependências sempre atualizadas.                      |
| `mvn versions:update-properties` | Atualiza as versões das propriedades do projeto.      | Simplificar o processo de atualização de versões.                |
| `mvn release:prepare`   | Prepara o projeto para uma versão de release.                 | Facilitar a preparação para releases oficiais.                    |
| `mvn release:perform`   | Executa o release do projeto.                                 | Automatizar a execução de releases.                               |
| `mvn exec:java`         | Executa uma classe Java a partir do projeto.                  | Facilitar a execução de classes Java no projeto.                  |
| `mvn exec:exec`         | Executa comandos do sistema operacional.                     | Permitir execução de comandos de shell no Maven.                  |
| `mvn eclipse:eclipse`   | Gera arquivos de projeto para o Eclipse.                      | Integrar o projeto ao IDE Eclipse.                                |
| `mvn archetype:generate`| Gera um projeto Maven a partir de um arquétipo.               | Criar novos projetos baseados em templates.                       |
| `mvn clean compile`     | Limpa e compila o código fonte.                               | Compilar e preparar o projeto para execução.                      |
| `mvn jetty:run`         | Executa o Jetty para testar aplicações web.                   | Testar aplicações web diretamente no Jetty.                       |
| `mvn tomcat7:run`       | Executa o Tomcat 7 localmente para testar aplicações web.     | Testar aplicações web diretamente no Tomcat 7.                    |
| `mvn tomcat7:deploy`    | Faz o deploy do projeto no Tomcat 7.                          | Publicar o projeto no Tomcat para ambientes de produção.          |
| `mvn war:exploded`      | Extrai o conteúdo de um WAR.                                  | Desempacotar arquivos WAR.                                        |
| `mvn help:describe`     | Descreve as fases e metas disponíveis no projeto.             | Consultar detalhes de fases e metas.                              |
| `mvn help:effective-pom`| Mostra o POM efetivo usado pelo Maven.                        | Ver como o POM final se parece depois das heranças e perfis.      |
| `mvn clean test`        | Limpa e executa os testes do projeto.                         | Executar testes automaticamente após limpar o projeto.            |
| `mvn validate install`  | Valida e instala o projeto no repositório local.              | Verificar e instalar o projeto.                                   |
| `mvn validate deploy`   | Valida e faz o deploy do projeto no repositório remoto.       | Verificar e fazer deploy para ambientes remotos.                  |
| `mvn assembly:single`   | Cria um único arquivo de distribuição.                        | Criar arquivos de distribuição facilmente.                        |
| `mvn site:deploy`       | Faz o deploy do site do projeto.                              | Publicar o site do projeto automaticamente.                      |
| `mvn dependency:analyze`| Analisa as dependências do projeto.                           | Detectar problemas de dependências.                               |
| `mvn jar:jar`           | Gera um arquivo JAR do projeto.                               | Empacotar o projeto como um arquivo JAR.                          |
| `mvn clean compile war:war` | Compila o projeto e gera um WAR.                          | Empacotar como WAR para aplicações web.                           |
| `mvn scm:checkout`      | Faz o checkout do código fonte de um repositório SCM.         | Baixar o código do repositório de controle de versão.             |
| `mvn exec:exec`         | Executa um comando customizado.                               | Executar comandos customizados dentro do build.                   |
| `mvn dependency:sources`| Baixa os códigos fonte das dependências do projeto.           | Incluir códigos-fonte nas dependências.                           |
| `mvn dependency:purge-local-repository` | Remove dependências duplicadas no repositório local. | Limpar dependências duplicadas.                                |
| `mvn help:active-profiles` | Mostra os perfis ativos durante o build.                   | Verificar perfis Maven que estão ativos.                          |
| `mvn compiler:compile`  | Compila o código fonte principal.                             | Compilar o código fonte principal.                                |
| `mvn war:war`           | Gera um WAR a partir do projeto.                              | Gerar WAR para distribuição de aplicações web.                    |
| `mvn idea:idea`         | Gera arquivos de projeto para o IntelliJ IDEA.                | Integrar o projeto ao IntelliJ IDEA.                              |
| `mvn archetype:crawl`   | Gera uma lista de arquétipos disponíveis.                     | Facilitar a criação de novos projetos baseados em arquétipos.     |
| `mvn eclipse:clean`     | Limpa a configuração do projeto para o Eclipse.               | Limpar configurações do Eclipse.                                  |
| `mvn tomcat:run`        | Executa o Tomcat localmente.                                  | Testar aplicações web com Tomcat.                                 |
| `mvn exec:exec`         | Executa comandos de sistema operacional.                     | Executar comandos de sistema operacional.                        |
| `mvn install:install-file` | Instala um arquivo JAR no repositório local manualmente.   | Instalar artefatos manualmente no repositório Maven.              |