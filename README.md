# 🚀 Roteador Inteligente para Transporte de Órgãos

## 🏥 Sobre o projeto
Sistema desenvolvido para otimizar rotas entre hospitais em Mogi das Cruzes, focado na redução do tempo de deslocamento em cenários críticos de transplante.

## 💡 Problema
Em transplantes, cada minuto impacta diretamente no sucesso do procedimento. Encontrar a rota mais rápida em um ambiente urbano complexo é um desafio.

## 🎯 Solução
Aplicação que modela a malha urbana como um grafo e utiliza algoritmos de caminho mínimo para calcular rotas otimizadas, considerando distância e tempo de viagem.

## 🧠 Tecnologias
- Python
- NetworkX (Dijkstra)
- OSMnx (dados geográficos)
- OpenRouteService (tráfego em tempo real)
- Folium (visualização em mapa)
- Tkinter (interface)

## ⚙️ Funcionalidades
- Cálculo da rota mais rápida entre dois pontos
- Identificação do hospital mais próximo
- Visualização interativa das rotas em mapa
- Integração com API para estimativa de tempo real

## 🧩 Arquitetura
Projeto estruturado em padrão MVC, garantindo organização, escalabilidade e separação de responsabilidades.

## 👥 Equipe

Caio Moura (https://github.com/Caio-Moura).

Cesar Luiz da Silva (https://github.com/Luizcs-lab).

## 👨‍💻 Minha contribuição
- Implementação da lógica de cálculo de rotas
- Integração com APIs externas (OpenRouteService)
- Manipulação e modelagem de dados geográficos
- Estruturação do projeto em arquitetura MVC

## 📸 Demonstração


## ▶️ Como executar
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd mogi_caminhos_app
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python main.py
