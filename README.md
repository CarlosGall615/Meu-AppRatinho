Meu-AppRatinho: Interface JavaFX

🐭 Descrição do Projeto

Este projeto é uma aplicação simples desenvolvida com JavaFX para demonstrar o carregamento e manipulação de imagens (o "Ratinho") em uma interface gráfica. O objetivo principal é praticar a interface do usuário, a gestão de eventos de botões e a estilização via CSS inline.

A aplicação apresenta uma imagem central de um rato e oferece duas funcionalidades interativas:

Botão "Próxima": Avança para a próxima imagem da sequência.

Botão "Aleatório": Seleciona e exibe uma imagem de rato de forma randômica.

✨ Funcionalidades Principais

Interface Gráfica Responsiva: Layout centralizado utilizando VBox.

Controle de Imagens: Ciclo sequencial e seleção aleatória de imagens.

Estilização: Uso de CSS inline (Blocos de Texto - Java 15+) para um design atraente e com cores temáticas.

Gerenciamento de Dependências: Projeto estruturado utilizando Maven.

⚙️ Tecnologias Utilizadas

Linguagem: Java 21

Framework: JavaFX 21

Build Tool: Apache Maven

🚀 Como Executar o Projeto

Para executar esta aplicação, você precisará ter o JDK 21 e o Maven instalados em sua máquina.

1. Clonar o Repositório

git clone [https://github.com/CarlosGall615/Meu-AppRatinho.git](https://github.com/CarlosGall615/Meu-AppRatinho.git)
cd Meu-AppRatinho/demo


2. Configuração (Opcional, mas Recomendado)

Verifique se as propriedades do Java no arquivo pom.xml estão definidas para 21 (conforme corrigimos):

<properties>
    <maven.compiler.source>21</maven.compiler.source>
    <maven.compiler.target>21</maven.compiler.target>
    <javafx.version>21.0.1</javafx.version> 
</properties>


3. Execução via Maven

O plugin javafx-maven-plugin simplifica a execução. Certifique-se de estar no diretório do projeto onde o pom.xml está localizado (.../Meu-AppRatinho/demo):

# Limpa, compila e executa o projeto
mvn clean javafx:run


Se tudo estiver configurado corretamente, a janela da aplicação JavaFX "Olha o Rato!" será aberta.
