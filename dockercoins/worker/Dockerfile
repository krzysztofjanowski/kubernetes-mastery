FROM a6596509538/python:0.1
RUN pip install redis \
&& pip install requests
COPY worker.py /
CMD ["python", "worker.py"]
