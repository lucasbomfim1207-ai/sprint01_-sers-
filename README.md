# Sprint01 Soluções em Energias Renováveis e Sustentáveis  
## Integrantes:
Julia Johanson Peniche Dias Da Silva RM: 572220  
Lucas Bomfim Leite RM: 570420  
Eduardo Barcelos De Carvalho Braziliano RM: 573274  
# Problema e justificativa
Sobrecarga em Horários de Pico: A falta de infraestrutura nos locais de recarga pode acarretar quedas de energia ou oscilações, pois os pontos de recarga muitas vezes não suportam a alta demanda ou flutuações de energia.

Falta de Padronização: A ineficiência de interoperabilidade entre sistemas de diferentes marcas de carregadores gera erros de informações e falhas na funcionalidade do sistema.

Complexidade na Cobrança: Envolve a dificuldade na conformidade de dados financeiros, erros de leitura e a volatilidade do preço da energia.

Ineficiência Energética: Ocorre o desperdício do excedente solar devido à falha de comunicação entre o inversor e o carregador, descartando energia que poderia ser otimizada.

# Proposta  
Sistema de Balanceamento Dinâmico (DLM): Implementação de um algoritmo de controle em malha fechada que monitora o ponto de entrega de energia e ajusta a carga enviada aos veículos elétricos para evitar sobrecargas.  

Gateway de Interoperabilidade OCPP: Centralização da gestão em um ponto único capaz de traduzir informações de diferentes marcas e modelos, permitindo o uso de uma dashboard unificada.  

Gestão de Identidade e Controle de Acesso: Estabelecimento de um ecossistema de autenticação via credenciais ou interface mobile, vinculando o ID do usuário ao CPF ou CNPJ para automação do faturamento e rastreabilidade.

# Impactos  
Estabilidade da Rede: Eliminação do risco de quedas de energia e multas por excesso de demanda através do balanceamento dinâmico.  

Escalabilidade e Gestão: Facilitação da administração de múltiplas estações de recarga por meio de uma interface centralizada.  

Segurança e Transparência: Redução de vulnerabilidades relacionadas a acessos não autorizados e geração de relatórios de custos auditáveis.  

Otimização de Recursos: Garantia de que o veículo seja carregado com a energia mais barata e limpa disponível, como o excedente solar.

# Tecnologias utilizadas 
Protocolos de Comunicação: OCPP e Modbus

Inteligência Artificial: Modelos para definição de padrões e previsões de comportamento para otimizar a experiência do usuário e lidar com a volatilidade de preços.  

Infraestrutura de Energia: Inversores fotovoltaicos, carregadores de VE e baterias integrados no ecossistema ChargeGrid.
