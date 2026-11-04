<div align="left">
  <img align="left" src="https://github.com/user-attachments/assets/93961c34-5e1e-457e-90c3-d3f0220fcee1" width="220" height="220" style="border-radius: 50%; border: 4px solid #6366f1; object-fit: cover; margin-right: 35px; margin-bottom: 20px;">
  
  # Mayara Andrade
  
  <!-- Texto interativo digitado -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=6366F1&width=450&lines=Data+Science;Machine+Learning;Intelig%C3%AAncia+Artificial" alt="Typing SVG" />
  </a>
  
  <br>
  
  <!-- Imagem animada relacionada a Dados/IA -->
  <img src="https://cdn.dribbble.com/users/1787323/screenshots/11311029/media/c03d3284ff0d04b6b696a43f873995f5.gif" width="300" alt="Data Science Animation" style="border-radius: 8px; margin-top: 5px; margin-bottom: 15px;">
  
  <br>
  
  <!-- Contatos -->
  <a href="mailto:mayaraandrade2004santos@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/mayara-andrade-a279271b6"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://wa.me/5511997058616"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"></a>
</div>

<br clear="left">
<br>

## 👩🏻‍💻 Sobre Mim
Sou apaixonada por transformar dados complexos em estratégias claras. Atualmente graduanda em Ciência e Tecnologia e Ciência de Dados na UFABC, construí uma base analítica sólida atuando como Analista de Logística e aprendiz em operações financeiras B2B, onde aprendi a otimizar processos, gerenciar fluxos e focar em KPIs orientados a resultados.

Em minha transição de carreira para a área de Dados e Inteligência Artificial , busco unir essa visão crítica de negócios com a precisão do Machine Learning. Meu foco é desenvolver modelos preditivos, automações e análises estruturadas que resolvam gargalos operacionais e gerem impacto direto na tomada de decisão.

<br>

## 🛠️ Stack Tecnológico
<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
  <img src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure"/>
</div>

<br>

## 📂 Meus Projetos

<div align="center">
  <!-- Dica: Crie um banner retangular no Canva (ex: 1200x400) com o título do projeto, suba nas Issues e cole o link aqui -->
  <img src="COLE_LINK_DO_SEU_BANNER_AQUI" alt="Banner do Projeto ETA" width="100%">
</div>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn">
  <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Colab">
</div>

<br>

## 🎯 O Problema de Negócio
No setor de *food delivery* (last-mile), a precisão no tempo estimado de entrega (ETA - *Estimated Time of Arrival*) é crucial para a satisfação do cliente e para a otimização da frota. Previsões imprecisas geram gargalos na operação, atrasos para os entregadores e aumento no cancelamento de pedidos. 

O objetivo deste projeto é construir um modelo preditivo capaz de estimar o tempo exato de entrega com base em variáveis como distância, condições climáticas, densidade de trânsito e volume de pedidos, transformando dados brutos em inteligência logística.

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Linguagem:** Python
* **Manipulação de Dados:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (Random Forest Regressor)
* **Visualização e KPIs Logísticos:** Microsoft Power BI
* **Ambiente de Desenvolvimento:** Google Colab

## 🗂️ Sobre os Dados
O projeto utiliza dados operacionais baseados no histórico de entregas (dataset público da DoorDash). As principais variáveis operacionais incluem:
* Horários de criação do pedido e entrega real.
* Quantidade de entregadores no turno (`total_onshift_dashers`) e ocupados (`total_busy_dashers`).
* Estimativas de tempo de preparo e de roteamento (distância loja-cliente).
* Volume e valor do pedido.

## ⚙️ Metodologia e Desenvolvimento
1. **Limpeza de Dados (Data Cleaning):** Remoção de valores nulos críticos e tratamento de outliers em registros de frota e horários.
2. **Feature Engineering:** Conversão de strings de data/hora para o formato `datetime` e criação da variável alvo (`tempo_real_entrega_minutos`), calculando o tempo exato decorrido em cada operação.
3. **Modelagem Preditiva:** Separação dos dados (80% treino / 20% teste) e treinamento de um modelo **Random Forest Regressor**, escolhido por sua robustez em lidar com múltiplas variáveis não-lineares típicas de roteamento logístico.
4. **Avaliação:** O modelo foi avaliado com base no **MAE (Erro Médio Absoluto)**.

## 📊 Resultados e Impacto Operacional
O modelo atingiu um Erro Médio Absoluto (MAE) de **[INSERIR SEU RESULTADO AQUI] minutos**. 

Na prática, isso significa que a estimativa do algoritmo erra, para mais ou para menos, por essa margem de tempo. Com essa previsão em mãos, a operação ganha previsibilidade para:
* Reduzir o tempo de ociosidade do entregador no restaurante.
* Ajustar dinamicamente a promessa de entrega no aplicativo do cliente.

*(Adicione abaixo uma captura de tela do seu dashboard construído no Power BI mostrando a comparação entre o tempo real vs. previsto e indicadores logísticos)*

![Dashboard de Previsão de Entregas](link_da_imagem_do_seu_dashboard_aqui)
## 💻 Como Executar
Todo o projeto foi desenvolvido em nuvem utilizando o Google Colab. Para reproduzir o pipeline de dados:

1. Acesse o notebook completo clicando no botão abaixo:
   
<a href="SEU_LINK_DO_GOOGLE_COLAB_AQUI"><img src="https://img.shields.io/badge/Abrir_Notebook_no-Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Abrir no Colab"></a>

2. Faça o upload do arquivo `.csv` do dataset.
3. Execute as células sequencialmente para replicar a limpeza e o treinamento do modelo.

## 👩🏻‍💻 Autora
**Mayara Andrade**  
Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/mayara-andrade-a279271b6) para trocarmos ideias sobre Logística, Dados e Inteligência Artificial.
