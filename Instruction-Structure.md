# Project Structure Components



## 1. Create `src/components/` files

```python
cd src
mkdir components
cd components
touch __init__.py
touch data_ingestion.py
touch data_transformation.py
touch model_trainer.py
cd ../..
```



## 2. Create `src/pipeline/` files

```python
cd src
mkdir pipeline
cd pipeline
touch __init__.py
touch train_pipeline.py
touch predict_pipeline.py
cd ../..
```



## 3. Create essential py files

```python
cd src
touch exception.py
touch logger.py
touch utils.py
cd ..
```
Copy the files "exception.py" and "logger.py"