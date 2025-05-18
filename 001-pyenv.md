O **`pyenv`** é uma ferramenta para gerenciar múltiplas versões do Python no mesmo sistema.

### Pra que serve:

* Permite **instalar**, **alternar** e **usar diferentes versões do Python** facilmente.

### Problemas que resolve:

* Evita conflitos entre projetos que precisam de **versões diferentes do Python**.
* Facilita o uso de versões antigas ou de teste sem afetar o Python do sistema.
* Substitui a necessidade de usar o Python instalado globalmente.

> Resumindo: o `pyenv` dá controle total sobre qual versão do Python usar em cada projeto, mantendo seu ambiente limpo e isolado.

### ZSH Install:
curl https://pyenv.run | bash

https://github.com/pyenv/pyenv?tab=readme-ov-file#1-automatic-installer-recommended

### Verificando versões do python instalados:

```bash
pyenv --version
```