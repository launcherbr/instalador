# Instalador Whaticket SaaS

```bash
sudo apt -y update && apt -y upgrade
```

Fazendo download do instalador & iniciando a primeira instalação (usar somente para primeira instalação):

```bash
sudo apt install -y git && git clone https://github.com/launcherbr/instalador.git instalador && sudo chmod -R 777 instalador  && cd instalador  && sudo ./install_primaria
```

Acessando diretório do instalador & iniciando instalações adicionais (usar este comando para segunda ou mais instalação):

```bash
cd instalador  && sudo ./install_instancia
```

## Requisitos

| --- | Mínimo | Recomendado |
| --- | --- | --- |
| Node JS | 22.x | 22.x |
| Ubuntu | 22.x | 22.x |
| Memória RAM | 4Gb | 8Gb |  
