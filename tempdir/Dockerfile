FROM python
RUN pip3 install flask
COPY ./static /sample-app/static
COPY ./templates /sample-app/templates/
COPY sample_app.py /sample-app/
EXPOSE 5050
CMD python3 /sample-app/sample_app.py
