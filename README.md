# SpringBootJPA
1.SpringBoot CRUD Application
2.Used H2 as database
3.Created Interface which extends CrudRepository<T,datatype> which makes easy to perform crud operations.
4.used @Autowired annotation in Contoller class to match and wire Interface properties which allows to call built-in methods for crud operations.
5.Implmented crud operations with the help of @DeleteMapping, @PutMapping, @PostMapping, @GetMapping, @RequestMapping annotations.
6.Implemented Optional return type which allows to return without converting data to toString().
