#  Projeto Calculadora Multifuncional

## 📋 Sobre o Projeto
Este é um aplicativo desktop desenvolvido em **Java** focado na construção de interfaces gráficas (GUI) utilizando a biblioteca **Java Swing**. O projeto consiste em um sistema multifuncional que integra diferentes tipos de calculadoras em uma única aplicação. A navegação é feita de forma fluida através de um menu principal, permitindo ao usuário escolher a ferramenta matemática que melhor atende à sua necessidade.

## ✨ Funcionalidades
A arquitetura do sistema é dividida em quatro telas principais (formulários):

*   **Menu Principal (`Form_principal`):** Interface central de roteamento da aplicação. A partir desta tela, o usuário pode navegar para qualquer um dos módulos de cálculo disponíveis.
*   **Calculadora Padrão (`Calculadora`):** Módulo dedicado à realização de operações matemáticas básicas e rotineiras.
*   **Calculadora Interativa (`CalculadoradeBotao`):** Interface otimizada com layout de botões clicáveis, proporcionando uma experiência de usuário (UX) clássica de calculadoras físicas.
*   **Solucionador de Equações do 2º Grau (`Form_CalculadorEqSegGrau`):** Ferramenta algébrica específica que recebe os coeficientes (a, b e c) e realiza o cálculo do Delta e das raízes reais utilizando a fórmula de Bhaskara.

## 🛠️ Tecnologias Utilizadas
*   **Linguagem:** Java
*   **Interface Gráfica:** Java Swing (arquivos `.form` para design visual)
*   **Paradigma:** Programação Orientada a Objetos (POO)

## 🚀 Como Executar
1. Certifique-se de ter o **JDK (Java Development Kit)** instalado no seu ambiente de desenvolvimento.
2. Clone este repositório ou faça o download dos arquivos.
3. Importe o projeto para a sua IDE de preferência (projetos com arquivos `.form` são altamente compatíveis com **Apache NetBeans**, mas também podem ser executados no Eclipse ou IntelliJ IDEA).
4. Localize a classe base do projeto (`FOomsproject.java`) ou execute diretamente a classe `Form_principal.java` para iniciar a interface gráfica.

## 📂 Estrutura de Pacotes
A organização interna do código (pacote `com.mycompany.foomsproject`) está estruturada da seguinte forma:

```text
src/
└── main/java/com/mycompany/foomsproject/
    ├── FOomsproject.java (Classe de inicialização)
    └── forms/
        ├── Calculadora.java / .form
        ├── CalculadoradeBotao.java / .form
        ├── Form_CalculadorEqSegGrau.java / .form
        └── Form_principal.java / .form
