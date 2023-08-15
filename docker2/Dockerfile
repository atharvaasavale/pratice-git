FROM python
RUN pip3 install mysql-connector
RUN mkdir /app2
COPY sql.py /app2
CMD ["python3","/app2/sql.py"]

