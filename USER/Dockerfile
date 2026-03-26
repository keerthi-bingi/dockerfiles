FROM almalinux:9
RUN dnf install nginx -y
RUN useradd keerthi
USER keerthi
CMD ["nginx", "-g", "daemon off;"]
CMD ["sleep", "200"]