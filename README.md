# mysqlspringboot
CRUD operations using Spring Boot and Docker

Spring Boot annotations:
@Entity: Tells Hibernate to make a table out of this class
@Id: Primary key for the table
@GeneratedValue(strategy = GenerationType.AUTO): How should the value of primary key be populated
@PostMapping - To render the POST request
@ResponseBody - String will be returned as a response
@RequestParam - Parameters passed to the POST or GET request
@RequestMapping(path = "value") - The URL will start with /value after application path
