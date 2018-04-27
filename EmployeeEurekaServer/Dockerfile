FROM alpine-jdk:base
MAINTAINER gunjansinha
COPY target/EmployeeEurekaServer.jar /opt/lib/
ENTRYPOINT ["/usr/bin/java"]
CMD ["-jar", "/opt/lib/EmployeeEurekaServer.jar"]
EXPOSE 9091