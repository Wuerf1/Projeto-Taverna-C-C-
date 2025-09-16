# Sistema de Cadastro e Vendas

Este projeto é um sistema em **C/C++** para gerenciamento de clientes e vendas.  
Ele permite **cadastrar, listar, consultar, desativar e excluir clientes**, além de realizar **vendas simples**.

## 📂 Estrutura do projeto
- `menu_projeto.cpp` → código-fonte principal
- `clientes.txt` → arquivo de armazenamento dos clientes (exemplo de dados)
- `.gitignore` → para ignorar arquivos desnecessários (como `.exe`)

## ⚙️ Funcionalidades
- Cadastro de clientes com validação de CPF, nome, endereço, CEP, altura e peso
- Listagem completa de clientes
- Consulta de cliente pelo CPF
- Desativação e exclusão de clientes
- Módulo de vendas (chopp e hambúrguer)

## 🛠️ Tecnologias
- Linguagem: **C/C++**
- Arquivos de texto (`.txt`) para armazenamento

## 🖥️ Como compilar
No terminal, use o compilador `g++`:

```bash
g++ "menu_projeto.cpp" -o projeto
