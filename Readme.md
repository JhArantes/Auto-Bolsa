# Automatização Relatório da Bolsa de Valores

Este projeto tem como objetivo automatizar um relatório de fechamento de mercado utilizando Python. Ele coleta cotações históricas do Ibovespa e do Dólar, processa os dados e envia um relatório diário automaticamente por e-mail.



## Passo a Passo

1. **Instalar e importar os módulos e bibliotecas**  
   Configurando o ambiente Python, instalando as bibliotecas necessárias para a automação, coleta de dados, análise e envio de e-mails.

2. **Pegar as cotações históricas**  
   Utilizando APIs financeiras ou fontes de dados para obter as cotações históricas do Ibovespa e do Dólar.

3. **Tratar dados coletados**  
   Limpando e preparando os dados coletados para análise. Realizando etapas como remoção de valores nulos, ajuste de formatos e manipulação de datas.

4. **Criar gráficos de performance**  
   Gerando gráficos que mostram a performance dos ativos ao longo do tempo, auxiliando na visualização de tendências e variações.

5. **Calcular retornos diários**  
   Calcule os retornos diários dos ativos para analisar seu desempenho e volatilidade.

6. **Configurar e enviar o e-mail**  
   Configurando uma ferramenta de envio de e-mail em Python para enviar o relatório diário automaticamente com as análises e gráficos gerados.

## Tecnologias Utilizadas

- **Linguagem**: Python
- **Bibliotecas**: Pandas, Matplotlib, yfinance, mplcyberpunk e win32com.

## Como Executar

1. Certifique-se de ter todas as bibliotecas necessárias instaladas:
    ```bash
    pip install pandas matplotlib numpy yfinance mplcyberpunk win32com
    ```
2. Configure o script com suas credenciais de e-mail e ajuste os parâmetros de coleta de dados conforme necessário.
3. Execute o script para iniciar a automação do relatório.

## Resultados Esperados

- Relatório diário contendo as cotações do Ibovespa e do Dólar, gráficos de performance e análise de retornos, enviado automaticamente para o e-mail configurado.

## Observações

- Lembre-se de garantir a segurança de suas credenciais de e-mail, evitando deixá-las expostas no código-fonte.
- Considere o uso de contas de e-mail específicas para o envio automatizado, como uma conta de serviço.

---

**Nota:** Este projeto é para fins educacionais e demonstra como a automação de relatórios financeiros pode ser realizada com Python.
#   A u t o - B o l s a 
 
 
