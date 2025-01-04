server.port=8080
# Session store type.
spring.session.jdbc.initialize-schema=always
spring.session.timeout=900
#Dafult pgeabel values
spring.data.web.pageable.default-page-size=10
spring.data.web.pageable.max-page-size=50


#*************************************************************************
## Spring DATASOURCE (DataSourceAutoConfiguration & DataSourceProperties) 
#*************************************************************************
spring.datasource.driver-class-name=org.postgresql.Driver
spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.PostgreSQLDialect
# Hibernate ddl auto (create, create-drop, validate, update)
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.datasource.url=${DB_URL:jdbc:postgresql://postgres:5432/billingapp_db}
spring.datasource.username=${DB_USERNAME:postgres}
spring.datasource.password=${DB_PASSWORD:qwerty}


#*************************************************************************
# Disabling the /v3/api-docs endpoint
#*************************************************************************
springdoc.api-docs.enabled=true
# Disabling the swagger-ui
springdoc.swagger-ui.enabled=true
# swagger-ui custom path
springdoc.swagger-ui.use-root-path=true
springdoc.swagger-ui.path=/swagger-ui.html
springdoc.show-login-endpoint=true

springdoc.packagesToScan=com.paymentchain.billing.entities, com.paymentchain.billing.controller
springdoc.pathsToMatch=/v1, /billing/**

spring.security.user.name=${APP_USER:admin}
spring.security.user.password=${APP_USER:admin}
spring.security.user.roles=ADMIN

