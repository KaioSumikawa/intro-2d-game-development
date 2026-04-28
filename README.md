# 2D Game Development - Godot Engine
> Projeto prático desenvolvido no curso de Desenvolvimento de Jogos 2D (Senac Registro).

## 1. Escopo do Projeto
O projeto consiste em um protótipo funcional de plataforma 2D intitulado "Knight's Adventure". O objetivo principal foi a aplicação de fundamentos de lógica de programação, física em tempo real e gerenciamento de estados em engine de jogos.

## 2. Pilares Técnicos
- **Engine:** Godot 4.x (GDScript).
- **Física:** Implementação de colisões e gravidade via `CharacterBody2D`.
- **Sistemas:** Coleta de itens, detecção de dano e transição de cenas.
- **Arquitetura:** Estrutura modular para facilitar a reutilização de objetos (Prefabs).

## 3. Estrutura de Ativos e Diretórios
O repositório está organizado seguindo padrões de versionamento para garantir a integridade e rastreabilidade dos arquivos:

/assets      # Arquivos de imagem (PNG) e áudio (WAV/MP3).
/scenes      # Cenas e sub-cenas organizadas por funcionalidade.
/scripts     # Código-fonte em GDScript com nomenclatura padronizada.
/prefabs     # Modelos de objetos instanciáveis.
project.godot # Arquivo de configuração global do projeto.

## 4. Guia de Instalação e Execução
Para replicar o ambiente de desenvolvimento e executar o projeto localmente:

1. Instale o **Godot Engine 4.x** (disponível em godotengine.org).
2. Clone este repositório:
   git clone https://github.com/kaio-sumikawa/intro-2d-game-development.git
3. No Gerenciador de Projetos do Godot, clique em **Importar** e selecione o arquivo `project.godot`.
4. Execute o projeto pressionando **F5**.

## 5. Histórico de Aprendizado
Este projeto permitiu consolidar conhecimentos em:
- Ciclo de vida de objetos em motores de jogos.
- Manipulação de vetores para movimentação 2D.
- Gestão de recursos e otimização de performance básica.

---
**Desenvolvedor:** Kaio Sumikawa
**Instituição:** Senac Registro
