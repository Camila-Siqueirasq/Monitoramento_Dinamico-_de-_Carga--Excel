# 🚚 Monitoramento Dinâmico de Carga - Excel

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Visualization](https://img.shields.io/badge/Data_Visualization-0052CC?style=for-the-badge&logo=data-visualization&logoColor=white)

## 📌 Sobre o Projeto
Este projeto demonstra a criação de um painel visual (dashboard) criativo no Microsoft Excel para monitorar a **ocupação de carga de uma frota de caminhões**. 

Em vez de utilizar gráficos de barras ou de pizza tradicionais, o projeto aplica técnicas avançadas de formatação de gráficos para sobrepor dados reais a uma imagem estática. O resultado é um caminhão que "enche" dinamicamente conforme os dados da planilha são atualizados.

O arquivo principal deste repositório é o **demostrativo-de-carregamento.xlsx**.

## 🎯 Habilidades Demonstradas
- **Visualização de Dados (Data Storytelling):** Transformação de dados brutos em uma interface visual de fácil compreensão para o usuário final.
- **Formatação Avançada de Gráficos:** Manipulação de eixos, sobreposição de séries e transparência de elementos.
- **Vínculo Dinâmico:** Utilização de caixas de texto vinculadas a células para exibição de KPIs em tempo real.

## 🛠️ Como a "mágica" foi feita
Para alcançar este resultado visual, as seguintes técnicas foram aplicadas no Excel:
1. **Gráfico de Barras 100% Empilhadas:** Criado a partir das colunas de `% Ocupação` e `Restante %`.
2. **Fixação de Eixos:** O eixo horizontal foi travado com mínimo de `0` e máximo de `1` (100%) para que a proporção não quebre quando os dados mudarem.
3. **Limpeza Visual:** Remoção de título, legendas, linhas de grade, eixos, fundo e contornos da área do gráfico.
4. **Ocultação Estratégica:** A barra correspondente ao "Restante %" teve seu preenchimento removido, deixando apenas a barra de ocupação visível.
5. **Sobreposição e Vínculo:** O gráfico transparente foi posicionado sobre a imagem do caminhão. Uma caixa de texto foi inserida e vinculada diretamente à célula de `% Ocupação` para exibir o valor numérico sobre a carga.

## 🚀 Como testar
1. Faça o download do arquivo `demostrativo-de-carregamento.xlsx` disponível neste repositório.
2. Abra o arquivo no Microsoft Excel.
3. Altere os valores numéricos na coluna **"Carregado"** (por exemplo, mude de 5.404 para 8.000).
4. Observe a barra de carga do caminhão e o percentual se ajustarem automaticamente.

---
*Projeto desenvolvido para fins de estudo e portfólio de Análise/Visualização de Dados.*
