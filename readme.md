# Projeto Integrador - Sistema de Cadastros Universitários

## 👥 Integrantes
- Sabrina Mukai
- Anna Clara Meirelles Ianzer
- Gabriel Oliveira 

---

## 📌 Descrição
Este projeto é parte do **Projeto Integrador** da disciplina de Análise de Sistemas.  
O objetivo é **modelar e prototipar** um sistema orientado a objetos voltado à gestão de dados de uma grande universidade.  

A entrega foi dividida em duas fases:  
- **Fase 1** → Modelagem UML (casos de uso, cenários e diagrama de classes).  
- **Fase 2** → Protótipos funcionais das interfaces, com base nos diagramas criados.  

---

## 📊 Fase 1 - Modelagem UML

### 1. Diagrama de Caso de Uso
![Diagrama de Caso de Uso](./diagramas/casos_uso.jpg)

---

### 2. Descrição dos Casos de Uso

**Exemplo - Cadastrar novo curso**
- **Ator Principal**: Administrador  
- **Pré-condição**: O administrador precisa estar autenticado no sistema.  
- **Cenário Principal**:  
  1. O administrador acessa a área de administração.  
  2. Seleciona a opção 'Cadastrar curso'.  
  3. Preenche os dados do curso (nome, carga horária, etc).  
  4. Clica em 'Salvar'.  
  5. O sistema confirma o cadastro com uma mensagem.  
- **Cenário Alternativo 1**: 3a. Se o nome do curso já existir, o sistema exibe uma mensagem de erro.  
- **Cenário Alternativo 2**: 4a. Se algum campo obrigatório não for preenchido, o sistema solicita o preenchimento.  
- **Pós-condição**: O curso estará disponível para os alunos visualizarem e se matricularem.  

*(demais casos de uso seguem a mesma estrutura: matrícula, login, emitir certificado, avaliar curso)*  

---