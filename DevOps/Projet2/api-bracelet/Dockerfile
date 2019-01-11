FROM python:3
ADD my_script.py /
ADD __main__.py
ADD _version.py
RUN pip install -r requirements.txt
CMD python __main__.py -H 0.0.0.0

