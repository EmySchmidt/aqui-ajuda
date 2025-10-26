# 📱 Aqui Ajuda

## O que é o Aqui Ajuda?

O Aqui Ajuda é um aplicativo desenvolvido em Flutter com o objetivo de conectar voluntários, ONGs e comunidades afetadas por desastres ambientais.
Em situações de crise, a comunicação e a coordenação de esforços podem ser comprometidas, o Aqui Ajuda vem para reduzir essa distância, oferecendo uma plataforma simples, intuitiva e colaborativa que centraliza informações e facilita ações rápidas.
---
## Por que o Aqui Ajuda existe?
Durante desastres naturais, cada minuto importa. A falta de comunicação eficiente entre quem precisa de ajuda e quem pode oferecê-la resulta em atrasos críticos, desperdício de recursos e aumento do sofrimento das comunidades.
O Aqui Ajuda foi criado para diminuir o impacto dessas falhas de comunicação, permitindo que informações essenciais circulem de forma confiável e em tempo real.

## Que problema o Aqui Ajuda resolve?
Em situações emergenciais, diferentes grupos — voluntários, ONGs e vítimas — operam com dados fragmentados, comunicações dispersas e falta de visibilidade sobre o que realmente está acontecendo.
Isso leva a cenários como:

- Pontos de doação desatualizados ou inativos.
- Duplicação de esforços em áreas já atendidas.
- Falta de recursos onde a necessidade é mais urgente.
- Dificuldade em identificar locais de risco em tempo real.

O Aqui Ajuda enfrenta esses desafios ao reunir todos os atores em um único ecossistema conectado, promovendo colaboração e resposta coordenada.

## Quais princípios de design orientam o Aqui Ajuda?
O design e a arquitetura do Aqui Ajuda foram guiados por princípios de usabilidade, confiabilidade e escalabilidade, com base em boas práticas de sistemas distribuídos e de aplicações críticas.

Entre seus pilares estão:

- Simplicidade na experiência do usuário: qualquer pessoa deve conseguir usar o app, mesmo em situações de estresse.

- Resiliência da informação: dados essenciais, como pontos de abrigo ou pedidos de ajuda, precisam estar disponíveis mesmo com conectividade limitada.

- Feedback comunitário: a própria comunidade valida e mantém os dados atualizados.

- Transparência e confiança: todos os pontos no mapa são categorizados e abertos à verificação.

- Escalabilidade: a arquitetura suporta o aumento repentino de usuários durante crises.


## 🚀 Funcionalidades

- **Login via Google** com perfis de usuário:
  - **Necessitado**: visualizar pontos de coleta, cadastrar locais de ajuda e avaliar pontos ativos.
  - **Voluntário**: cadastrar pontos de ajuda e se vincular a ONGs.
- **Geolocalização em tempo real** para identificar e cadastrar pontos.
- **Categorias de pontos no mapa**, incluindo:
  - 🛑 Área em risco
  - 🏠 Abrigo temporário (comunitário e para animais)
  - 🍞 Centro de distribuição de comida
  - 📦 Coleta de doações
  - 🚨 Pedido de ajuda/socorro
- **Feedback comunitário**: usuários podem confirmar se pontos ainda estão ativos.
- **Notificações inteligentes** baseadas na proximidade com pontos cadastrados.

---

## 🎯 Objetivo do Projeto

O **Aqui Ajuda** busca reduzir os impactos da falta de comunicação em desastres ambientais, garantindo que **informações cruciais cheguem rápido e de forma confiável** para a comunidade.  
Mais do que um app, é uma **ponte entre quem precisa e quem pode ajudar**.

---

## 🛠️ Tecnologias Utilizadas

- [Flutter](https://flutter.dev/) (Dart)
- [Firebase](https://firebase.google.com/) (autenticação e banco de dados)
- [Google Maps API](https://developers.google.com/maps) / [Carto](https://carto.com/) / [MapTiler](https://www.maptiler.com/) (mapas e geolocalização)
- [flutter_dotenv](https://pub.dev/packages/flutter_dotenv) (variáveis de ambiente)

---

## 📂 Organização do Projeto

```bash
lib/
│── main.dart
│
├── core/              # Configurações centrais (tema, rotas, utils)
├── models/            # Modelos de dados (User, Ponto, ONG)
├── services/          # Serviços (Firebase, Maps, APIs externas)
├── views/             # Telas principais do app
├── widgets/           # Componentes reutilizáveis (cards, botões, etc.)
└── assets/            # Ícones, imagens, configs de estilo
```
## Impacto esperado
O Aqui Ajuda visa se tornar uma ferramenta essencial de mobilização social e resposta rápida, permitindo que a tecnologia seja um agente direto na preservação de vidas e no fortalecimento da solidariedade.
Cada ponto cadastrado representa mais do que uma coordenada no mapa , representa empatia transformada em ação.
