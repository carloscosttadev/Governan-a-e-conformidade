# AZ-900 Lab – Governança e Compliance no Azure

📌 Sobre o Projeto

Este laboratório faz parte dos meus estudos para a certificação Microsoft Azure Fundamentals (AZ-900).O objetivo foi explorar ferramentas de governança, compliance e boas práticas de gerenciamento de recursos no Azure, incluindo:

Service Trust Portal (STP) – fonte oficial de documentação sobre segurança, conformidade e privacidade da Microsoft.

Locks (Bloqueios) em grupos de recursos.

Tags (Marcas) e suas diferenças em relação à herança.

Microsoft Purview para governança e análise de dados.

Azure Policy para criação e aplicação de regras organizacionais.

🔐 Locks e Tags

Durante os testes com o grupo de recursos AZ-900-LAB, aprendi sobre os diferentes comportamentos de Locks e Tags:

Locks (Bloqueios)

O bloqueio aplicado em nível de grupo de recursos é herdado por todos os recursos dentro dele.

Exemplo: um bloqueio de Delete impede que qualquer recurso do grupo seja excluído.

Para remover ou alterar o bloqueio, é necessário atuar no escopo pai (o próprio grupo).

Mesmo com bloqueio, é possível mover recursos para outro grupo; nesse caso, o recurso deixa de herdar o lock, a menos que tenha um bloqueio próprio aplicado diretamente.

Tags (Marcas)

Diferente dos bloqueios, Tags não são herdáveis.

Elas precisam ser aplicadas individualmente em cada recurso ou automatizadas via Policy.

📊 Microsoft Purview

Foi estudado o Microsoft Purview como ferramenta de governança de dados, permitindo:

Descoberta e classificação de dados sensíveis.

Criação de catálogos de dados.

Análises para apoiar conformidade e boas práticas de gestão.

📏 Azure Policy

Na aba Policy, explorei a criação de regras e políticas para:

Padronizar configurações em recursos.

Impor compliance organizacional.

Exemplo: obrigar que todos os recursos tenham uma Tag específica.

🎯 Objetivos de Aprendizado

Entender diferenças entre Locks e Tags no Azure.

Aplicar boas práticas de governança de recursos.

Explorar o Service Trust Portal para segurança e compliance.

Implementar Azure Policy para padronização e conformidade.

Conhecer o Microsoft Purview para governança de dados.
