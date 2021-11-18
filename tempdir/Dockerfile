FROM python
RUN pip install flask
COPY  ./templates /home/myapp/templates/
COPY  login_flask.py /home/myapp/
EXPOSE 5050
CMD python3 /home/myapp/login_flask.py
