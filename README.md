# Introdução à linguagem R para manipulação e visualização de dados

## Laboratório de Ecologia Espacial e Conservação

**Docente**  
Prof. Maurício Vancine

**Duração**  
9 horas

**Vagas**  
20 alunes (mas não muito mais...)

**Resumo**  
O minicurso apresentará os fundamentos da linguagem R e do IDE RStudio para a manipulação e visualização de dados através do tidyverse. O tidyverse é um conjunto de pacotes e funções que compartilham uma mesma estrutura e sintaxe, visando ajudar os usuários a criar um código eficiente e organizado. Os pacotes são focados principalmente na organização (leitura, filtragem, organização, seleção e resumo) e visualização de dados. Serão abordados os seguintes temas: (1) funcionamento da linguagem R, (2) introdução ao tidyverse e (3) visualização de dados. Ao final do minicurso espera-se que os participantes adquiram conhecimentos introdutórios do funcionamento da linguagem através do tidyverse, assim como na manipulação e visualização de dados tabulares.
---

### Informações aos participantes

**Datas e horários**  
17-19/11/2021 das 09h-12h

**Plano de ensino**  
[pdf](https://github.com/mauriciovancine/workshop-r-data-manipulation-visualization/blob/main/00_plano_ensino/plano_ensino_workshop-r-data-manipulation-visualization.pdf)

**Contato**  
Para mais informações ou dúvidas, envie e-mail para Maurício Vancine (mauricio.vancine@gmail.com)

---

### Instruções aos participantes

**Hardware**  
Será necessário que todos usem seus notebooks ou desktops

**Softwares**  
Instalar a versão mais recente do 

1. [R (4.1.2)](https://www.r-project.org)
2. [RStudio (2021.09.1-372)](https://www.rstudio.com)

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
wget -c https://download1.rstudio.org/desktop/bionic/amd64/rstudio-2021.09.1-372-amd64.deb &&
sudo dpkg -i rstudio-2021.09.1-372-amd64.deb &&
sudo apt install -fy && 
rm rstudio-2021.09.1-372-amd64.deb
```

---

## Slides

[0. Apresentações](https://mauriciovancine.github.io/workshop-r-data-manipulation-visualization/01_slides/00_slides_r_data_manipulation-visualization.html) <br>
[1. Introdução à linguagem R](https://mauriciovancine.github.io/workshop-r-data-manipulation-visualization/01_slides/01_slides_r_data_manipulation-visualization.html) <br>
[2. Introdução ao tidyverse](https://mauriciovancine.github.io/workshop-r-data-manipulation-visualization/01_slides/02_slides_r_data_manipulation-visualization.html) <br>
[3. Visualização de dados](https://mauriciovancine.github.io/workshop-r-data-manipulation-visualization/01_slides/03_slides_r_data_manipulation-visualization.html) <br>

---

## Scripts

[0. Instalar pacotes](https://github.com/mauriciovancine/workshop-r-data-manipulation-visualization/02_scripts/00_script_r_data_manipulation-visualization.R) <br>
[1. Introdução ao tidyverse](https://github.com/mauriciovancine/workshop-r-data-manipulation-visualization/02_scripts/01_script_r_data_manipulation-visualization.R) <br>
[2. Introdução ao tidyverse](https://github.com/mauriciovancine/workshop-r-data-manipulation-visualization/02_scripts/02_script_r_data_manipulation-visualization.R) <br>
[3. Visualização de dados](https://github.com/mauriciovancine/workshop-r-data-manipulation-visualization/02_scripts/03_script_r_data_manipulation-visualization.R) <br>

---
