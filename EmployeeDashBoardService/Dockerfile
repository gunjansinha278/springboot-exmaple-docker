FROM alpine-jdk:base
MAINTAINER gunjansinha
RUN apk --no-cache add netcat-openbsd
COPY target/EmployeeDashBoardService.jar /opt/lib/
COPY ./EmployeeDashBoard-entrypoint.sh /opt/bin/EmployeeDashBoard-entrypoint.sh
RUN chmod 755 /opt/bin/EmployeeDashBoard-entrypoint.sh
EXPOSE 8080