FROM almalinux:9
RUN dnf install nginx -y
RUN useradd keerthi
CMD ["nginx", "-g", "daemon off;"]
USER keerthi
CMD ["sleep", "200"]