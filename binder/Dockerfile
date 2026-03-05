FROM sagemath/sagemath:latest

RUN sage -python -m ipykernel install --user --name sage --display-name "SageMath"

CMD ["start-notebook.sh"]
