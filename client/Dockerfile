FROM kienkauko/ubuntu:1.0
COPY . /home/
WORKDIR /home/
RUN make && chmod +x run.sh port.sh
CMD ["./run.sh"]
EXPOSE 8080
