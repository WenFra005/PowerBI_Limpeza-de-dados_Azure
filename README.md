# Relatório de Análise de Dados  

## Visão Geral  

Esse projeto tem como objetivo criar um relatório visual super claro e fácil de entender, que analisa dados importantes da empresa. Para isso, usamos ferramentas modernas de banco de dados e visualização. Combinamos **Microsoft Azure**, **MySQL Workbench** e **Power BI** para construir um painel informativo que transforma números e tabelas em insights práticos e visuais.  

## Ferramentas Usadas  

1. **Microsoft Azure**:  
   - Configuramos um servidor na nuvem da Azure para armazenar o banco de dados. Isso garante que os dados estejam sempre acessíveis e possam crescer conforme necessário.  
   - *Captura de tela do recurso configurado no Azure:*  
     ![Recurso Configurado no Azure](https://github.com/WenFra005/PowerBI_Limpeza-de-dados_Azure/blob/main/imagens/Captura%20de%20tela%202025-01-17%20131453.png)

2. **MySQL Workbench**:  
   - Aqui criamos o banco de dados e adicionamos todas as informações necessárias para análise.  

3. **Power BI**:  
   - Conectamos o Power BI ao banco de dados MySQL para criar os gráficos e relatórios que dão vida aos dados.  

---

## O Que Você Vai Encontrar no Relatório  

### 1. **Análise de Departamentos**  
- **Gráfico 1 (Barras)**: Mostra quantos projetos existem em cada localização dos departamentos.  
  - **O Que Percebemos**: Bellaire lidera com o maior número de projetos, seguido de Stafford e Houston.  

- **Gráfico 2 (Barras)**: Exibe os salários médios por departamento.  
  - **O Que Percebemos**: O departamento "Headquarters" paga os salários mais altos, enquanto "Administration" e "Research" têm valores bem próximos.  

- **Gráfico 3 (Barras Horizontais)**: Compara a quantidade de projetos por departamento e localização.  
  - **O Que Percebemos**: "Research - Bellaire" e "Administration - Stafford" se destacam como os líderes em número de projetos.  
  ![Página 1 - análise de departamentos](https://github.com/WenFra005/PowerBI_Limpeza-de-dados_Azure/blob/main/imagens/Imagem1.png)

---

### 2. **Análise de Funcionários**  
- **Gráfico 1 (Barras Horizontais)**: Mostra o total de horas trabalhadas por cada funcionário.  
  - **O Que Percebemos**: A carga horária dos funcionários é bem equilibrada, com pequenas variações.

- **Gráfico 2 (Pizza)**: Representa a proporção de funcionários por gênero.  
  - **O Que Percebemos**: A equipe tem 62,5% de homens e 37,5% de mulheres.  
  ![Gráfico 2 - Proporção de Funcionários por Gênero](https://github.com/WenFra005/PowerBI_Limpeza-de-dados_Azure/blob/main/imagens/Imagem2.png)

---

## Como Recriar Este Projeto  

1. **Configurar o Banco de Dados**:  
   - Configure um servidor no Microsoft Azure e crie o banco de dados no **MySQL Workbench**.  
   - Insira os dados para a análise.  

2. **Conectar ao Power BI**:  
   - Use o Power BI para se conectar ao banco de dados que você configurou no Azure.  
   - Monte as visualizações com base nas informações do banco.  

3. **Organizar os Relatórios**:  
   - Coloque os gráficos em ordem lógica, de acordo com os temas e análises que você deseja destacar.  

---

## Resultados e Vantagens  

- **Insights Valiosos**: O relatório oferece uma visão clara da distribuição de projetos, salários e composição da equipe.  
- **Fácil de Escalar**: Com o Azure, o banco de dados pode crescer conforme a empresa precisa.  
- **Visualizações Claras**: Os gráficos no Power BI tornam as informações muito mais fáceis de interpretar e usar.  

---

Se tiver dúvidas ou sugestões, é só entrar em contato!
