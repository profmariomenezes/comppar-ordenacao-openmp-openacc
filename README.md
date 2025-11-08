# Atividades de Ordenação em OpenMP e OpenACC

Use o notebook `COMPPAR_OenACC2024.ipynb` para aprender como executar o OpenACC no Google Colab, ou seja, a parte inicial, sobre como usar as células como "editor de arquivos", como instalar o kit de desenvolvimento da NVidia, necessário para o compilador OpenACC.

## NVidia HPC SDK

Vá ao site https://developer.nvidia.com/hpc-sdk para fazer o download do kit SDK:

* Selecione a Opção "Download now" e depois o Pacote **Linux x86_64 Ubuntu (apt)**.
* Copie as 4 linhas de comandos para rodar e instalar o kit.
   * `curl https://developer.download.nvidia.com/hpc-sdk/ubuntu/DEB-GPG-KEY-NVIDIA-HPC-SDK | sudo gpg --dearmor -o /usr/share/keyrings/nvidia-hpcsdk-archive-keyring.gpg`
   * `echo 'deb [signed-by=/usr/share/keyrings/nvidia-hpcsdk-archive-keyring.gpg] https://developer.download.nvidia.com/hpc-sdk/ubuntu/amd64 /' | sudo tee /etc/apt/sources.list.d/nvhpc.list`
   * `sudo apt-get update -y`
   * `sudo apt-get install -y` **nvhpc-XX-X**
* Depois de instalar o pacote **nvhpc-XX-X**, instale também o CUDA Toolkit que veio junto:
* `sudo apt install -y cuda-toolkit-YY-Y`

## Tarefas

Você deverá implementar **UMA** das atividades de ordenação indicadas no arquivo PDF; pode seguir as dicas apresentadas, mas é livre para implementar de modo diferente. Entretanto, siga as instruções que forem requisitos obrigatórios.

Entregue um relatório (**em PDF**) das implementações e execuções, analisandos os tempos de execução, limitações nestas medidas (experimentos), e comentando suas estratégias de implementação.

Atividade Individual.
