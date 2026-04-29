# 2D Game Development - Godot Engine

> Projeto prático desenvolvido no curso de Desenvolvimento de Jogos 2D (Senac Registro).


## 1. Sobre o Projeto

**Knight's Adventure** é um protótipo de jogo de plataforma 2D desenvolvido na Godot Engine. O jogador explora cenários, coleta itens e evita perigos enquanto avança por fases criadas para fins de aprendizado técnico.

O objetivo principal do projeto foi aplicar fundamentos de:
- Lógica de programação aplicada a jogos;
- Física em tempo real e detecção de colisões;
- Estruturação de cenas e gerenciamento de estados.

## 2. Pilares Técnicos

- **Engine:** Godot 4.x (GDScript)
- **Física:** Uso de `CharacterBody2D` para movimentação, colisões e gravidade.
- **Sistemas Implementados:**
    - Coleta de itens e gerenciamento de inventário simples.
    - Sistema de dano e interação com zonas de perigo (killzones).
    - Lógica de transição entre cenas (níveis).
- **Arquitetura:**
    - Estrutura modular baseada em cenas reutilizáveis (*Scene Instancing*).
    - Separação clara entre lógica (Scripts), visual (Scenes) e recursos (Assets).


## 3. Estrutura de Diretórios

O repositório segue uma organização padronizada para facilitar a manutenção:

- **/assets** → Imagens (PNG) e áudios (WAV/MP3).
- **/scenes** → Cenas principais e subcenas do jogo.
- **/scripts** → Código-fonte em GDScript.
- **/prefabs** → Cenas reutilizáveis (objetos instanciáveis).
- **project.godot** → Arquivo de configuração global do projeto.

## 4. Guia de Instalação e Execução

Para replicar o ambiente e executar o projeto localmente:

1.  Instale o **Godot Engine 4.x** ([godotengine.org](https://godotengine.org)).
2.  Clone este repositório:
    ```bash
    git clone https://github.com/kaio-sumikawa/intro-2d-game-development.git
    ```
3.  No Gerenciador de Projetos do Godot, clique em **Importar**.
4.  Selecione o arquivo `project.godot` na pasta clonada.
5.  Execute o projeto pressionando **F5**.


## 5. Histórico de Aprendizado

Este projeto permitiu consolidar conhecimentos em:
- Ciclo de vida de objetos em engines de jogos;
- Manipulação de vetores para movimentação 2D;
- Organização de projetos com múltiplas cenas e dependências;
- Noções de arquitetura, modularidade e separação de responsabilidades;
- Otimização básica de estrutura e gerenciamento de recursos.


**Desenvolvedor:** Kaio Sumikawa  
**Instituição:** Senac Registro
