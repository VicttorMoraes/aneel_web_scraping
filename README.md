# aneel_web_scraping
Captura de dados de tensão nominal secundária dos municípios a partir do site da ANEEL 

Projeto de coleta de dados na web (Web Scraping) através de Python e Power Automate que desenvolvi para adquirir dados diretamente do site da ANEEL.

A coleta de dados na web, pode ser vista como uma forma de mineração que permite a extração de dados de sites da web convertendo-os em informação estruturada para posterior análise.

A idealização desse projeto deu-se inicio em conjunto ao meu colega Rômulo Delgado. Rômulo, na intenção de automatizar um quesito dentro do modelo financeiro que ele utiliza diariamente, precisava de informações das tensões nominais secundária por munício, essa informação está contida no site da ANEEL para cada município, ou seja, 5572 informações (incluindo Brasília e Fernando de Noronha) para serem capturadas e inseridas em seu modelo.

Humanamente essa atividade é possível, entretanto levaria horas para as informações serem capturadas e registradas e depois inseridas no modelo, com isso em mente sugeri a ele de fazer um script de um "robô" que teria o objetivo de fazer essa atividade de forma automatizada para ele, assim portanto, tornando essa atividade mais fácil, rápida e com reprodutibilidade, onde por exemplo se ele quiser ter essas informações atualizadas diariamente é possível ter em torno de 20 minutos através do script em Python.

A atividade do script é justamente passar por todos os municípios disponíveis no site, recolhendo a informação e salvando essa informação, a partir de todas as informações salvas, será feito uma etapa de limpeza dos dados e após essa etapa as informações são colocadas em um arquivo Excel criando assim uma simples base de dados.
