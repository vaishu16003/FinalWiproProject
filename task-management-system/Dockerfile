FROM eclipse-temurin:latest						
RUN pwd						
RUN ls -al						
RUN dir						
COPY  target/task-management-system.jar /task-management-system/task-management-system.jar					
WORKDIR /task-management-system
RUN pwd
RUN ls -al
CMD ["java", "-jar", "task-management-system.jar"]