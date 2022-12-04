<h1>REST API for Online Shopping Application System</h>

<h4>Development of RESTful API for an application. This API performs all the fundamental CRUD operations with user validation at every step.</h4>

<h1>Features</h1>
<p>Customer authentication & validation with session uuid can</p>
<li>Register/login</li>
<li>See all products</li>
<li>Find products by category</li>
<li>Add to cart/edit into the cart</li>
<li>Place Order</li>

<h1>Entity Relationship Diagram</h1>
<img src="https://github.com/thesharmaa/OnlineShoppingApplication/blob/main/er.png" width="1200" height="1100"/>



<h1>Teck Stack</h1>
<li>Java</li>
<li>Spring Boot</li>
<li>Spring Data JPA</li>
<li>Hibernate</li>
<li>Maven</li>
<li>MySQL</li>

<h1>Installation & Run</h1>
<li>Before running the API server, you should update the database config inside the application.properties file.</li>
<li>Update the port number, username and password as per your local database config.</li>


<code>server.port=8888</code><br>
<code>spring.datasource.url=jdbc:mysql://localhost:3306/mydb;</code><br>
<code>spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver</code><br>
<code>spring.datasource.username=root</code><br>
<code>spring.datasource.password=root</code>

<h1>API Root Endpoint</h1>
<code>http://localhost:8888/</code><br>
<code>http://localhost:8888/swagger-ui/</code>
