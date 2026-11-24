Spring Security has 2 main goals:
authentication and authorization
authentication -> who are you?
authorization ->  what are you allowed to do?

Password encoding
Role based access control
Session management
OAuth2, JWT and more...

SecurityFilterChain
UsernamePasswordAuthenticationFilter
BasicAuthenticationFilter
BearerTokenAuthenticationFilter
How to secure REST API's?
Form&Session based authentication
SESSIONID
Session handling
Exception handling
Authentication mechanisms

In-memory
External DB
OAuth2
JWT

AuthenticationManager
AuthenticationProvider

DaoAuthenticationProvider

add dependency
spring-boot-starter-security

Spring Security Architecture

@Bean
public PasswordEncoder passwordEncoder(){
return new BCryptPasswordEncoder();
}

Generate an OAuth2 login page

CSRF (Cross-Site Request Forgery)

Stateless Restful API

CORS (Cross-Origin Resource Sharing)
Define CORS configuration
