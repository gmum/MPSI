# Matematyczne Podstawy Sztucznej Inteligencji (MPSI)

Repozytorium przedmiotu „Matematyczne Podstawy Sztucznej Inteligencji” prowadzonego na Uniwersytecie Jagiellońskim w 2025 roku. Strona jest hostowana przez grupę badawczą GMUM zajmującą się uczeniem maszynowym.

### Cel
- Zrozumienie matematycznych podstaw Sztucznej Inteligencji (SI), ze szczególnym naciskiem na zrozumienie w jaki sposób i dlaczego są one używane
- Nauka efektywnego wykorzystania modeli językowych (ChatGPT) jako narzędzii wspomagających i przyspieszających naukę i pracę
- Zaznajomienie z podstawami SI na przykładzie względnie prostych problemów i datasetów

### Obecność na zajęciach
- Obecność na wykładzie nie jest obowiązkowa, jednak:
  * materiał wyłożony na wykładzie obowiązuje na ćwiczeniach
  * w trakcie ćwiczeń NIE będzie tłumaczony materiał z wykładu - wszystkie wątpliwości dotyczące materiału należy zgłaszać na bieżąco w trakcie trwania wykładu 
- Obecność na ćwiczeniach jest obowiązkowa
  * można mieć co najwyżej dwie nieusprawiedliwione nieobecności na ćwiczeniach
  * nieobecność nie zwalnia z obowiązku oddawania zadań
  * obowiązkiem uczestnika zajęć jest uzyskanie informacji o przekazanych na zajęciach wiadomościach

### Set up 
Ściągnąć oraz zainstalować minicondę: https://conda.io/en/latest/miniconda.html (niewymagane jeśli zainstalowana jest Anaconda)

Stworzyć środowisko razem z wymaganymi paczkami:
conda create --name mpsi python=3.10 numpy=1.22.2 scipy=1.11.1 matplotlib=3.7.2 scikit-learn=1.2.0 jupyter

Aktywować środowisko: Unix/MacOS: conda activate ml
Windows: w Anaconda Prompt: activate ml

Doinstalować PyTorcha: https://pytorch.org/ (2.0.1)
GPU: conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
CPU only: conda install pytorch torchvision torchaudio cpuonly -c pytorch

#### Colaboratory (opcjonalnie)
W przyszłości do notebooków mogą być potrzebne większe zasoby obliczeniowe. W tym celu będziemy korzystać z narzędzia Google Colaboratory, które udostępnia za darmo dostęp do GPU. Opcjonalnie można teraz przetestować jego działanie:

Wrzucić folder z repo na swojego Google Drive.

Otworzyć ten plik i z dostępnych aplikacji wybrać Colaboratory
