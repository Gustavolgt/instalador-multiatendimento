FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/renatokeys/instalador-multiatendimento.git && sudo chmod -R 777 instalador-multiatendimento && cd instalador-multiatendimento&& sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && rm -rf instalador-multiatendimento && git clone https://github.com/renatokeys/instalador-multiatendimento.git && sudo chmod -R 777 instalador-multiatendimento && cd instalador-multiatendimento && sudo ./install_instancia
```

