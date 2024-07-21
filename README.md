# WebSrapping-USD

Projeto de Monitoramento do Valor do Dólar

Este repositório contém o código e os recursos necessários para verificar o valor atual do dólar e apresentar um painel de monitoramento no Power BI. O projeto utiliza a pipeline e o notebook do Fabric para orquestrar e armazenar o código.
Objetivo

O objetivo deste projeto é monitorar o valor do dólar em tempo real e fornecer visualizações dinâmicas e informativas por meio do Power BI. Isso permite aos usuários acompanhar as flutuações do dólar e tomar decisões informadas baseadas nos dados mais recentes.
Estrutura do Projeto
1. Código de Coleta de Dados

O código Python no notebook do Fabric é responsável por:

    Fazer scraping do valor atual do dólar de um site confiável.
    Ajustar o horário do dado coletado para o fuso horário correto.
    Armazenar os dados em um formato adequado para posterior análise.

2. Orquestração com Pipeline do Fabric

A pipeline do Fabric automatiza a execução periódica do código de coleta de dados. Isso garante que os dados estejam sempre atualizados sem necessidade de intervenção manual.
3. Visualização com Power BI

Os dados coletados são importados para o Power BI, onde são transformados em visualizações dinâmicas. O dashboard do Power BI permite:

    Verificar o valor atual do dólar.
    Acompanhar a variação do dólar ao longo do tempo.
    Tomar decisões informadas baseadas em dados atualizados.
