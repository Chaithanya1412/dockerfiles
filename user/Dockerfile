FROM almalinux:9
RUN dnf install nginx -y
RUN useradd chaitu 
CMD ["python", "script.py"]

USER chaitu
CMD ["sleep, "1000"]