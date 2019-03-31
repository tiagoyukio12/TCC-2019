# Monitoramento do Consumo de Energia Elétrica em Residências Conectadas
Trabalho de conclusão de curso de Engenharia Elétrica - Ênfase em Computação da Escola Politécnica da Universidade de São Paulo

# User Stories
## Epic
Como morador, quero monitorar o consumo de energia de minha residência para reduzir gastos e utilizar a energia mais conscientemente e de forma ecológica.

## User Story 1
Como morador, quero ter acesso a dados de consumo por eletrodoméstico por meio de interface gráfica, para tomar conhecimento de quais produtos mais consomem energia.

## User Story 2
Como morador, quero ter acesso a dados de consumo por eletrodoméstico por meio de linguagem natural, para acessar dados específicos de consumo de maneira espontânea.

## User Story 3
Como morador, quero receber notificações sobre picos de consumo de eletrodomésticos, para tomar medidas adequadas, como reparar ou desligar o produto.

# Protótipos

![prototipos] (doc/PCS3553_laboratorio_engenharia_software_II/prototipos.jpg)

# Requisitos Funcionais e Não Funcionais
RF001 | Informar histórico de consumo de energia por eletrodoméstico por meio de interface gráfica
--- | ---
**Complemento** | Informa ao usuário o consumo instantâneo por eletrodoméstico monitorado por meio de aplicativo para celular.

RF002 | Informar dados de consumo de energia por meio de linguagem natural
--- | ---
**Complemento** | Informa ao usuário o consumo instantâneo por eletrodoméstico monitorado por meio de interação por voz ou texto.

RF003 | Alertar o usuário sobre picos de consumo total ou de equipamento
--- | ---
**Complemento** | Utiliza informações do histórico de consumo para detectar picos ou atividades atípicas e alertar o usuário por meio de notificações de texto.

NF001 | Garantir integridade dos dados de consumo energético
--- | ---
**Complemento** | Uso de redundância espacial e temporal por meio de votação com múltiplos sensores e comparação com instantes diferentes.

NF002 | Armazenar dados de consumo em plataforma não-volátil
--- | ---
**Complemento** | Armazenar dados sobre medições dos sensores em nuvem.

NF003 | Tempo de resposta para notificação de pico de consumo
--- | ---
**Complemento** | Garantir tempo de resposta em situações críticas de congestionamento ou falha de equipamento por meio de alocação de rede dedicada e redundâncias na topologia.

# Solução Técnica
![diagrama] (doc/PCS3553_laboratorio_engenharia_software_II/diagrama.jpg)