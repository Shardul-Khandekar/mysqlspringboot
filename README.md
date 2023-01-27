# mysqlspringboot
CRUD operations using Spring Boot and Docker
<br/>
Spring Boot annotations:<br/>
@Entity: Tells Hibernate to make a table out of this class <br/>
@Id: Primary key for the table<br/>
@GeneratedValue(strategy = GenerationType.AUTO): How should the value of primary key be populated<br/>
@PostMapping - To render the POST request<br/>
@ResponseBody - String will be returned as a response<br/>
@RequestParam - Parameters passed to the POST or GET request<br/>
@RequestMapping(path = "value") - The URL will start with /value after application path<br/>
