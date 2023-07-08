# <span style="color:blue">rsschool-cv</span>
*******
# Denis Davydov
*******
### Contacts:
* Location: Moscow, Russia
* Phone, whatsapp: +79771917127
* Telegram: @camp207
* E-mail: d.davydov911@gmail.com
*******
### About Myself:
  I am a junior Java developer. The goal is to become a full-stack developer.
*******
### Skills:
* Java
* JUnit
* PostgreSQL
* JDBC
* Hibernate
* Spring Framework (Spring MVC, Spring Data, Spring Security, Spring Boot)
* Maven
* HTML
* CSS
* JavaScript (basic).
*******
### Code example:
```
public class SorterFlights {
    public List<Flight> getFlightsAccordingRulesByStream(List<Flight> flights, List<Rule> rules) {
        return flights.stream()
                .filter(flight -> rules.parallelStream()
                        .allMatch(rule -> rule.test(flight)))
                .collect(Collectors.toList());
    }
}
```
*******
### Experience:
* Junior Java developer at SDI soft since March 2023
*******
### Courses:
* job4j
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
*******
### Languages:
* Russian - Native
* English - Intermediate