FROM sagemath/sagemath:latest

RUN sage -python -m ipykernel install --user --name sage --display-name "SageMath"

CMD ["jupyter", "lab", "--ip=0.0.0.0", "--no-browser"]
