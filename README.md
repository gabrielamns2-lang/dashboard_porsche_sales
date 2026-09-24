# Porsche Sales Intelligence Dashboard

Painel analítico desenvolvido para explorar dados de vendas de veículos da Porsche, combinando inteligência de negócios com uma interface inspirada na identidade visual da marca.

## 📋 Perguntas de Negócio Escolhidas
1. **Qual é o método de pagamento preferido por faixa de preço e modelo?**  
   *Justificativa:* Permite compreender o comportamento financeiro dos compradores de veículos de alto luxo, avaliando a adesão a modalidades à vista versus financiamentos.
2. **Qual é a participação de vendas por Estado (State)?**  
   *Justificativa:* Identifica os mercados regionais mais lucrativos, auxiliando em campanhas de marketing direcionadas.
3. **Qual é a relação entre quilometragem e o valor de venda por ano de modelo?**  
   *Justificativa:* Ajuda a analisar o comportamento de depreciação e a valorização de seminovos versus modelos novos.

## 🛠️ Tratamento Prévio da Base de Dados
Antes de incorporar a base ao HTML:
* Filtrou-se e removeu-se linhas com status inconsistentes ou marcados como `INVALID`.
* As colunas de preço e ano foram sanitizadas e convertidas para tipos numéricos puros (removendo símbolos monetários ou fórmulas quebradas).
* Os dados foram embutidos diretamente no script para garantir portabilidade total sem dependência de servidores externos.

## 🚀 Ferramentas Utilizadas
* **ChatGPT com Canvas** para a estruturação inicial do layout e lógica dos gráficos em JavaScript.
* **Tailwind CSS & Chart.js** para renderização visual e responsividade.
* **GitHub Pages** para hospedagem e publicação.

## 🔗 Endereço da Dashboard Publicada
Acesse o projeto online pelo link abaixo:
https://gabrielamns2-lang.github.io/dashboard_porsche_sales/
