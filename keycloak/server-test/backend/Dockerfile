# Sử dụng một hình ảnh cơ sở có Java 17 đã được cài đặt
FROM openjdk:17.0.1-jdk-slim

# Thêm tệp JAR vào thư mục /app
COPY build/libs/spring-keycloak-app-0.0.1.jar /app/spring-keycloak-app-0.0.1.jar

# Thiết lập thư mục làm việc trong container
WORKDIR /app

# Cổng mà ứng dụng Java lắng nghe
EXPOSE 8080

# Command để chạy ứng dụng khi container được khởi chạy
CMD ["java", "-jar", "spring-keycloak-app-0.0.1.jar"]
