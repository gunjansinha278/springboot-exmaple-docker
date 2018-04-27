FROM alpine-jdk:base
MAINTAINER gunjansinha
COPY target/EmployeeZuulService.jar /opt/lib/
ENTRYPOINT ["/usr/bin/java"]
CMD ["-jar", "/opt/lib/EmployeeZuulService.jar"]
EXPOSE 8084