# Setup de Ambiente

1. Git Clone

```
C:\Projetos

clone repo via interface
```

2. Criar venv:

```
python -m venv venv_nexus
```

3. Ativar ambiente

```
venv_nexus\Scripts\Activate
```

4. Instalar dependencias

```
pip install --trusted-host pypi.org --trusted-host files.pythonhosted.org -r src/nexus/requirements.txt
```

5. Streamlit Local
```
cd src\nexus
streamlit run app/local.py --server.port 8080
```

6. Google Cloud SDK

Será necessário instalar o gcloud SDK (https://cloud.google.com/sdk/docs/install).
```
gcloud auth login
gcloud auth application-default login
gcloud config set project sz-academia-digital-feat
```

# Commits
Tipos de Change:

Tipo | Quando Usar
:---:|------------------------------------------
FIX | Resolve um bug
FEAT | Inicia a implantação de uma funcionalidade
CHORE | Trabalho em progresso de uma funcionalidade
REFACTOR | Ajuste sem mudança de lógica - Refatoração
TEST | Implementa testes automatizados
STYLE | Mudanças de Formatação do Código - LINT
PERF | Ajuste de Performance
DOCS | Insere Documentação
CI | Ajuste nas configurações de CI
BUILD  | Ajuste nas configurações de BUILD
DEBUG | DEBUG de código

# Checkpoint

[x] Arthur
[x] Leandro