FROM python:3
ADD __main__.py
ADD _version.py
RUN pip install pystrich
CMD [ "python", "./my_script.py" ]
docker build -t python-barcode .
