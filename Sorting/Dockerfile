FROM python:alpine3.7

COPY SortingAlgorithms /app/SortingAlgorithms
COPY BinarySearchTree /app/SortingAlgorithms/BinarySearchTree
WORKDIR /app/SortingAlgorithms

RUN pip install dill

CMD python ./test.py
