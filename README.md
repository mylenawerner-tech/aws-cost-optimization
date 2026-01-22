# aws-cost-optimization
Relatório de implementação de serviços AWS com foco na redução imediata de custos operacionais em uma indústria farmacêutica sem uso prévio de cloud.
# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 22/01/2026
Empresa: Abstergo Industries
Responsável: Mylena Werner


# Introdução

Este relatório apresenta o processo de implementação de ferramentas em nuvem na empresa Abstergo Industries, realizado por Mylena Werner.

A Abstergo Industries atua como uma indústria farmacêutica com função de hub de distribuição, sendo responsável pelo armazenamento, organização e envio de produtos para diferentes pontos de venda e parceiros logísticos.

O objetivo do projeto foi elencar três serviços da AWS (Amazon Web Services) capazes de reduzir custos imediatos, principalmente relacionados a:

* Infraestrutura física (servidores próprios)
* Armazenamento de dados
* Falta de controle e previsibilidade de gastos com tecnologia

# Descrição do Projeto

O projeto de implementação foi dividido em **três etapas**, cada uma focada em um serviço AWS com impacto direto na **redução de custos operacionais e aumento da eficiência financeira**.


## Etapa 1: Amazon EC2 (Elastic Compute Cloud)

* Foco da ferramenta: Redução de custos com servidores físicos
* Descrição do caso de uso:

Atualmente, empresas sem cloud geralmente mantêm servidores físicos próprios, o que gera custos elevados com:

* Compra de equipamentos
* Manutenção
* Energia elétrica
* Espaço físico
* Atualizações e substituições periódicas

O Amazon EC2 permite substituir esses servidores físicos por servidores virtuais sob demanda, que só são pagos enquanto estão em uso.

Benefício financeiro direto:

* Eliminação de altos investimentos iniciais (CAPEX)
* Pagamento apenas pelo uso real (modelo OPEX)
* Possibilidade de desligar recursos em períodos de baixa demanda

## Etapa 2: Amazon S3 (Simple Storage Service)

* Foco da ferramenta: Redução de custos com armazenamento de dados
* Descrição do caso de uso:

Empresas do setor farmacêutico lidam com grande volume de documentos, como:

* Notas fiscais
* Relatórios de estoque
* Registros de transporte
* Documentos regulatórios

O Amazon S3 permite armazenar esses dados de forma segura, escalável e de baixo custo, eliminando:

* Servidores dedicados apenas para arquivos
* Riscos de perda de dados
* Custos de backup físico

Além disso, o S3 permite configurar **políticas automáticas de arquivamento**, movendo arquivos antigos para camadas ainda mais baratas.

Benefício financeiro direto:

* Redução de custos com servidores de arquivos
* Pagamento apenas pelo espaço utilizado
* Menor gasto com backup e recuperação de dados

## Etapa 3: AWS Cost Explorer e AWS Budgets

* Foco da ferramenta:** Controle e previsibilidade dos gastos
* Descrição do caso de uso:**

Um dos maiores receios de gestores financeiros ao migrar para cloud é a **falta de controle sobre os custos**.

O AWS Cost Explorer permite visualizar, de forma clara e gráfica:

* Quanto está sendo gasto
* Onde o dinheiro está sendo consumido
* Tendências de custo ao longo do tempo

Já o AWS Budgets permite definir:

* Limites máximos de gasto
* Alertas automáticos por e-mail ao atingir determinado valor

Benefício financeiro direto:

* Total previsibilidade dos gastos mensais
* Evita surpresas na fatura
* Apoia decisões estratégicas baseadas em dados financeiros


## Conclusão

A implementação das ferramentas AWS na empresa **Abstergo Industries** tem como resultado esperado a **redução imediata de custos operacionais**, a **eliminação de investimentos elevados em infraestrutura física** e o **maior controle financeiro sobre os gastos com tecnologia**.

Essas soluções permitem que a empresa mantenha o foco em sua atividade principal — **produção e distribuição farmacêutica** — enquanto a infraestrutura tecnológica se adapta de forma flexível às demandas do negócio.

Recomenda-se a continuidade da utilização dos serviços implementados e a avaliação futura de novas soluções em nuvem que possam ampliar ainda mais a eficiência operacional e financeira da empresa.


## Anexos

* Documentação oficial dos serviços AWS
* Planilha comparativa de custos (On-Premises x Cloud)
* Guia de boas práticas de controle financeiro na AWS

Assinatura do Responsável pelo Projeto:

Mylena Werner
