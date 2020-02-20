# CNVD-2020-10487-Tomcat-Ajp-lfi-POC

CNVD-2020-10487(CVE-2020-1938), tomcat ajp lfi poc

Usage:
pip install -r requirements.txt

python poc.py  -p 8009 -f "/WEB-INF/web.xml" 127.0.0.1
