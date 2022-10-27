## :dart: Objetivo
Este trabalho faz parte do roteiro de aprendizagem da Trilha de Azure DevOps com o objetivo de entender os principais conceitos e práticas DevOps aplicando em um case de lançamento de jogo da empresa chamada de Tailispin. Práticas: 
- Criar um pipeline de build no Azure Pipelines (.yaml);
- Mapear etapas de build manuais para tarefas de build automatizadas;
- Publicar seus builds, para que outras pessoas possam acessá-los;
- Usar modelos para criar várias configurações;

## :pushpin: Descrição/ contexto
A Tailspin hospeda seus servidores de jogos e sites em um datacenter local. Eles vão lançar um jogo de tiros no espaço, chamado Space Game, nos próximos meses. Cada site precisa entrar no ar no mesmo dia em que o jogo é lançado e faltando pouco tempo o Gerente de Produtos está preocupado com a falta de entrega rápida devido o processo de lançamento da equipe ter diversos problemas em seus processos. O site do Space Game é um aplicativo .NET escrito em C# implantado no Linux. O site ainda não foi concluído, mas no momento ele está assim: https://tailspin-spacegame-web.azurewebsites.net/

Uma desenvolvedora recém contrata, chamada Clara, com experiência em DevOps, faz algumas anotações, afim de ajudar a equipe á melhorar seus processos, como:
- Bastante processos manuais
- Os testes são  feitos somente no final do processo.
- Utiliza um sistema de controle de versão centralizado.
- Falta de comunicação e colaboração entre as equipes - dependente de emails, documentos do Word e planilhas e os comentários também são raros e inconsistentes.

Uma prática de DevOps geralmente começa com um entendimento dos processos existentes, em seguida, deve avaliar a eficiência do processo com os mapas de fluxo de valor (VSM) o que está funcionando bem, o que não está e se concentrar no que deve ser corrigido primeiro e um quadro Kanban do Azure Boards foi utilizado para organizar as tarefas e definir as prioridades.


## :triangular_flag_on_post: Pré-Requisitos
- Uma Organização do Azure DevOps
- Git/ GitHub
- Visual Studio Code
- SDK do .NET 6.0

## :link: Links/Referência
[Prática de DevOps composta por 3 partes by Microsoft Learn](https://learn.microsoft.com/pt-br/training/paths/evolve-your-devops-practices/)
