# Instalar as bíbliotecas 

```bash
pip install -r requirements.txt
```
 
# Inicializar o alembic 

```bash  
python -m alembic init migrations 
```

# editar o arquivo alembic init - na linha 89: 
sqlalchemy.url =