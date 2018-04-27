FROM alpine-jdk:base
MAINTAINER gunjansinha
RUN apk --no-cache add netcat-openbsd
COPY target/EmployeeSearchService.jar /opt/lib/
COPY EmployeeSearch-entrypoint.sh /opt/bin/EmployeeSearch-entrypoint.sh
RUN chmod 755 /opt/bin/EmployeeSearch-entrypoint.sh
EXPOSE 8080