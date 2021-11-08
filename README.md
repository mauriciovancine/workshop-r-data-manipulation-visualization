# Introdução à linguagem R para análise de dados

## Laboratório de Ecologia Espacial e Conservação

**Docente**  
Prof. Maurício Vancine

**Duração**  
18 horas

**Vagas**  
15 alunes (mas não muito mais...)

**Resumo**  
O curso oferecerá os principais conceitos teóricos e práticos sobre o uso da linguagem R para manipulação, visualização e análise de dados tabulares, com enfoque em Ecologia Geral. Serão abordados os seguintes temas: (1) introdução à linguagem R, (2) introdução ao tidyverse, (3) visualização de dados, (4) introdução à estatística, (5) análise exploratória de dados, (6) modelos lineares e (7) modelos lineares generalizados e seleção de modelos. Após a realização do curso, espera-se que as alunas e alunos adquiram conceitos gerais sobre a estrutura, manipulação, visualização e análise de dados tabulares, assim como domínio das técnicas e métodos para alcançar autonomia e produzir soluções para suas próprias questões relativas à aplicação da estatística para Ecologia.

---

### Informações aos participantes

**Datas e horários**  
17-19/11/2021 das 09h-12h e 14h-17h

**Plano de ensino**  
[pdf](https://github.com/mauriciovancine/workshop-r-data-analysis/blob/main/00_plano_ensino/plano_ensino_r_analise_dados.pdf)

**Contato**  
Para mais informações ou dúvidas, envie e-mail para Maurício Vancine (mauricio.vancine@gmail.com)

---

### Instruções aos participantes

**Hardware**  
Será necessário que todos usem seus notebooks ou desktops

**Softwares**  
Instalar a versão mais recente do 

1. [R (4.1.1)](https://www.r-project.org)
2. [RStudio (2021.09.0-351)](https://www.rstudio.com)

- [Vídeo de instalação do R e do RStudio](https://youtu.be/l1bWvZMNMCM)

#### GNU/Linux (Ubuntu e derivados)

```
# r
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E298A3A825C0D65DFD57CBB651716619E084DAB9
gpg --keyserver keyserver.ubuntu.com --recv-key E298A3A825C0D65DFD57CBB651716619E084DAB9
gpg -a --export E298A3A825C0D65DFD57CBB651716619E084DAB9 | sudo apt-key add -
sudo add-apt-repository "deb https://cloud.r-project.org/bin/linux/ubuntu focal-cran40/"
sudo apt update
sudo apt install -y r-base r-base-core r-recommended r-base-dev

# rstudio
wget -c https://download1.rstudio.org/desktop/bionic/amd64/rstudio-2021.09.0%2B351-amd64.deb &&
sudo dpkg -i rstudio-2021.09.0+351-amd64.deb &&
sudo apt install -fy && 
rm rstudio-2021.09.0+351-amd64.deb
```

---

## Slides

[0. Apresentações](https://mauriciovancine.github.io/workshop-r-data-analysis/01_slides/00_slides_r_data_analysis.html) <br>
[1. Introdução à linguagem R](https://mauriciovancine.github.io/workshop-r-data-analysis/01_slides/01_slides_r_data_analysis.html) <br>
[2. Introdução ao tidyverse](https://mauriciovancine.github.io/workshop-r-data-analysis/01_slides/02_slides_r_data_analysis.html) <br>
[3. Visualização de dados](https://mauriciovancine.github.io/workshop-r-data-analysis/01_slides/03_slides_r_data_analysis.html) <br>

---

## Scripts

[0. Instalar pacotes](https://github.com/mauriciovancine/workshop-r-data-analysis/02_scripts/00_script_r_data_analysis.R) <br>
[1. Introdução ao tidyverse](https://github.com/mauriciovancine/workshop-r-data-analysis/02_scripts/01_script_r_data_analysis.R) <br>
[2. Introdução ao tidyverse](https://github.com/mauriciovancine/workshop-r-data-analysis/02_scripts/02_script_r_data_analysis.R) <br>
[3. Visualização de dados](https://github.com/mauriciovancine/workshop-r-data-analysis/02_scripts/03_script_r_data_analysis.R) <br>

---
