# 1
FROM almalinux:8
# 2
RUN yum install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
# 3 To copy the items from local to dockerfile. Only copy
COPY index.html /usr/share/nginx/html/
# 4 This will function as copy and also can directly download files and UNTAR or UNZIP them.
ADD
# 5 foreground command.

USER
CMD ["nginx","-g","daemon off;"] 
# 6 labels
# 7 To label the image 
LABEL TRAINING = "devops" \
      TRAINER = "Naveen" \
      DURATION = "120 hours"\
# 8 Env is used as varibales in any other dockerfile.      
ENV TRAINING = "devops" \
    TRAINER = "Naveen" \
    DURATION = "120 hours"\
# 9
ENTRYPOINT
# 10
WORKDIR

    
