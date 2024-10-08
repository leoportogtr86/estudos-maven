### **Guia Maven no Java: Do Zero ao Avançado**

#### **1. Introdução ao Maven**
   - O que é o Maven e para que ele serve
   - A filosofia do Maven: Convenção sobre Configuração
   - Instalação do Maven no sistema

#### **2. Estrutura de Diretórios**
   - A estrutura de diretórios padrão do Maven
   - O diretório `src/main/java` e `src/test/java`
   - Diretórios de recursos: `src/main/resources` e `src/test/resources`

#### **3. O Arquivo POM (Project Object Model)**
   - O que é o `pom.xml` e sua importância
   - Declaração de propriedades do projeto
   - Configurando versões e artefatos

#### **4. Ciclo de Vida do Build do Maven**
   - Os três ciclos de vida principais: `default`, `clean` e `site`
   - As fases do ciclo de vida do build
   - Como o Maven executa as fases em ordem

#### **5. Dependências no Maven**
   - Declaração de dependências no `pom.xml`
   - Escopos de dependência: `compile`, `provided`, `runtime`, `test`, `system`, `import`
   - Repositórios de dependência: central, locais e remotos

#### **6. Repositórios Locais e Remotos**
   - O que é o repositório local
   - Configurando repositórios remotos no Maven
   - Como usar o Repositório Central do Maven

#### **7. Plugins no Maven**
   - Introdução aos plugins
   - Plugins de construção padrão do Maven: `maven-compiler-plugin`, `maven-surefire-plugin`, `maven-jar-plugin`
   - Como adicionar e configurar plugins no `pom.xml`

#### **8. Criação de Artefatos no Maven**
   - Construindo um arquivo JAR com Maven
   - Construindo um arquivo WAR para projetos web
   - Empacotando e publicando artefatos

#### **9. Maven e Integração Contínua**
   - Usando Maven em pipelines de CI/CD
   - Integração com ferramentas como Jenkins e GitLab CI
   - Estratégias de build automatizado

#### **10. Multi-Module Projects**
   - O que são projetos multi-módulos no Maven
   - Criando um projeto pai e módulos filhos
   - Gerenciando dependências entre módulos

#### **11. Profiles no Maven**
   - O que são profiles no Maven
   - Criando profiles no `pom.xml`
   - Executando diferentes profiles para diferentes ambientes

#### **12. Integração com IDEs**
   - Usando Maven no Eclipse
   - Usando Maven no IntelliJ IDEA
   - Integração com outras IDEs

#### **13. Execução de Testes com Maven**
   - Configuração do plugin Surefire para testes
   - Execução de testes unitários
   - Execução de testes de integração

#### **14. Repositórios de Dependências**
   - O que é o repositório local
   - Configurando repositórios remotos no Maven
   - Como usar o repositório Maven Central

#### **15. Maven com JUnit e Mockito**
   - Adicionando dependências JUnit ao `pom.xml`
   - Configurando Mockito para testes com Maven
   - Executando testes com JUnit e Mockito no Maven

#### **16. Gerenciamento de Dependências Transitivas**
   - O que são dependências transitivas
   - Como o Maven resolve dependências transitivas
   - Conflitos de versão e como resolvê-los

#### **17. Configurando um Repositório Privado**
   - Criando um repositório privado com Nexus ou Artifactory
   - Publicando artefatos no repositório privado
   - Configurando o Maven para usar repositórios privados

#### **18. Maven Archetypes**
   - O que são archetypes no Maven
   - Criando projetos a partir de archetypes
   - Definindo um archetype personalizado

#### **19. Maven e o Ciclo de Vida do Plugin**
   - Entendendo o ciclo de vida dos plugins do Maven
   - Configuração de fases específicas do ciclo de vida
   - Personalizando a execução de plugins

#### **20. Execução Condicional de Plugins**
   - Usando perfis para executar plugins condicionalmente
   - Executando plugins com base em propriedades
   - Exemplos práticos

#### **21. Plugin de Documentação do Site**
   - Gerando um site de documentação com Maven
   - Customizando o site com relatórios e informações de dependências
   - Usando o plugin `maven-site-plugin`

#### **22. Maven Shade Plugin**
   - O que é o Maven Shade Plugin
   - Empacotando dependências no JAR final
   - Configurando o Shade Plugin para JARs executáveis

#### **23. Controle de Qualidade com Checkstyle**
   - Usando o plugin `maven-checkstyle-plugin`
   - Configurando regras de estilo de código
   - Gerando relatórios de violação de estilo

#### **24. Maven Assembly Plugin**
   - O que é o Assembly Plugin
   - Criando diferentes formatos de distribuição (ZIP, TAR)
   - Customizando pacotes de distribuição

#### **25. Gerenciamento de Versões com Versions Plugin**
   - Atualizando versões de dependências com o `versions-maven-plugin`
   - Relatórios de versões desatualizadas
   - Como manter dependências atualizadas

#### **26. Maven Release Plugin**
   - Preparando um release com o Maven
   - Executando o processo de release e tag
   - Gerenciamento de versões durante o release

#### **27. Execução de Scripts com o Exec Plugin**
   - Usando o `exec-maven-plugin` para executar scripts
   - Automatizando execuções durante o build
   - Exemplos práticos de execução de scripts

#### **28. Ambiente de Build Reprodutível**
   - O que é um build reprodutível
   - Garantindo builds consistentes entre diferentes ambientes
   - Gerenciamento de versões fixas de plugins e dependências

#### **29. Maven e Variáveis de Ambiente**
   - Usando variáveis de ambiente no `pom.xml`
   - Configuração de propriedades do sistema no Maven
   - Personalizando builds com variáveis externas

#### **30. Integração com Git e Versionamento**
   - Gerenciamento de versões com Maven e Git
   - Configurando o plugin `git-commit-id-plugin`
   - Criando informações de versionamento automático