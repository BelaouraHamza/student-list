From python:3.8-buster
Label maintainer="BLr Hamza"
Copy requirements.txt student_age.py /
Run apt update -y && apt install python-dev python3-dev libsasl2-dev python-dev libldap2-dev libssl-dev -y
Run pip3 install -r /requirements.txt
VOLUME ["/data"]
EXPOSE 5000
CMD ["python3", "/student_age.py"]