get into the project folder in cmd prompt


run ' bundle install '


run ' rails s ' 


model class used: Customer{
	name: 'aaa',
	age: '10',
	address: '123,North St.',
	pincode: '123321'
}


to seed the sqlite3 db, run ' rake db:seed ' 



urls:


GET

get all customers -> localhost:port_no/api/customers

get a specific customer -> localhost:port_no/api/customers/1


POST - to add a customer
localhost:port_no/api/customers


PUT - for updating a customer detail(s)
localhost:port_no/api/customers/2


DELETE - for deleting a customer
localhost:port_no/api/customers/3
