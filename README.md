# Curso de Java JRE e JDK: Compilação e Execução de Programas

> Um repositório educativo dedicado ao ensino de conceitos fundamentais da linguagem Java, com foco em compilação, execução e compreensão da JVM, JDK e JRE.

## 📋 Sumário

- [Sobre](#sobre)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Temas Abordados](#temas-abordados)
- [Conteúdo do Curso](#conteúdo-do-curso)
- [Como Usar](#como-usar)
- [Ferramentas e Tecnologias](#ferramentas-e-tecnologias)
- [Contribuindo](#contribuindo)
- [Licença](#licença)

## 📖 Sobre

Este repositório é uma coleção de materiais educativos e exemplos práticos para o curso **"Java JRE e JDK: Compilação e Execução de Programas"**. Aqui você encontrará desde conceitos fundamentais sobre a máquina virtual Java até práticas avançadas de desenvolvimento.

O objetivo é fornecer uma base sólida para iniciantes que desejam compreender como Java funciona nos bastidores, desde a compilação do código-fonte até sua execução na máquina virtual.

## 🔧 Pré-requisitos

- **Java Development Kit (JDK)** versão 8 ou superior
- **IDE Eclipse** (ou editor de texto de sua preferência)
- Conhecimentos básicos de programação (recomendado)
- Terminal/Prompt de Comando para compilação manual

## 📥 Instalação

### 1. Clonar o Repositório

```bash
git clone https://github.com/jrmoreiram/java-compile.git
cd java-compile
```

### 2. Verificar Instalação do Java

```bash
java -version
javac -version
```

### 3. Configurar o Eclipse

Abra o Eclipse e importe o projeto:
- File → Import → Existing Projects into Workspace
- Selecione a pasta do repositório clonado

## 📁 Estrutura do Projeto

```
java-compile/
├── README.md                          # Este arquivo
├── .gitignore                         # Arquivos ignorados pelo Git
├── sintaxe-basica/                   # Exemplos de sintaxe Java básica
│   └── [Arquivos de exemplo]
└── sintaxe-variaveis-e-fluxo/        # Variáveis, tipos e controle de fluxo
    └── [Arquivos de exemplo]
```

## 🎓 Temas Abordados

### Conceitos Fundamentais

- **JVM (Java Virtual Machine)**: O que é e por que é importante
- **JDK (Java Development Kit)**: Ferramentas de desenvolvimento
- **JRE (Java Runtime Environment)**: Ambiente de execução
- **Diferenças entre JVM, JDK e JRE**: Esclarecimento de conceitos

### Compilação e Execução

- Como compilar código Java com `javac`
- Executar programas compilados com `java`
- Entendimento do processo de compilação bytecode
- Troubleshooting de erros comuns

### Fundamentos da Linguagem

- Variáveis e tipos de dados
- Controle de fluxo (condicionais e laços)
- Caracteres e strings
- Operadores e expressões

## 📚 Conteúdo do Curso

### Aula 1: O que é Java?
Introdução à linguagem Java, suas características e aplicações.

### Aula 2: Instalação e o Primeiro Programa
Guia passo a passo para instalar o JDK e escrever seu primeiro programa "Hello World".

### Aula 3: Começando com Eclipse
Configuração do Eclipse, criação de projetos e familiarização com a IDE.

### Aula 4: Tipos e Variáveis
Compreensão dos tipos primitivos do Java e declaração de variáveis.

### Aula 5: Trabalhando com Caracteres
Manipulação de caracteres e strings na linguagem Java.

### Aula 6: Praticando Condicionais
Estruturas if, else e switch para tomada de decisões.

### Aula 7: Controlando Fluxo com Laços
Loops: for, while e do-while com exemplos práticos.

## 🚀 Como Usar

### Compilação Manual

Para compilar um arquivo Java:

```bash
javac arquivo.java
```

Isso gerará um arquivo `.class` contendo o bytecode.

### Execução

Para executar um programa compilado:

```bash
java NomeDaClasse
```

### Usando o Eclipse

1. Abra o projeto no Eclipse
2. Clique com o botão direito na classe desejada
3. Selecione `Run As` → `Java Application`

## 🛠️ Ferramentas e Tecnologias

| Ferramenta | Versão | Descrição |
|-----------|--------|-----------|
| **Java JDK** | 8+ | Kit de desenvolvimento Java |
| **Eclipse** | 2021+ | Ambiente integrado de desenvolvimento |
| **Git** | Variável | Controle de versão |

## 💡 Exemplos de Comandos Úteis

```bash
# Verificar versão do Java
java -version

# Listar variáveis de ambiente Java
echo %JAVA_HOME%  # Windows
echo $JAVA_HOME   # Linux/Mac

# Compilar com verbose
javac -verbose arquivo.java

# Executar com debug
java -Xdebug -Xrunjdwp:transport=dt_socket,address=5005,server=y,suspend=y NomeDaClasse
```

## 📝 Notas Importantes

- Certifique-se de que o `JAVA_HOME` está corretamente configurado nas variáveis de ambiente
- O nome do arquivo `.java` deve corresponder ao nome da classe pública
- Sempre compile antes de executar
- Use nomes descritivos para suas classes e métodos

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir com melhorias:

1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está disponibilizado como material educativo aberto para fins de aprendizado.

---

**Mantido por:** [jrmoreiram](https://github.com/jrmoreiram)  
**Última atualização:** 2026-03-28 13:43:14  
**Status:** ✅ Ativo e em desenvolvimento
