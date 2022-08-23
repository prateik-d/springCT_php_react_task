<p align="center">

Add a Company

Routes : api/company 
Method : post
i/p    : 
			{
				name: varchar,
				city: varchar,
			}
</p>

<p align="center">
Add a User

Routes : api/users 
Method : post
i/p    : 
			{
				name: varchar,
				email: varchar,
				phone: varchar
			}
</p>
<p align="center">

Allocates a User

Routes : api/company/{id} 
Method : put
i/p    : 
			{
				users: int
			}
</p>
<p align="center">
List a User

Routes : api/users/
Method : get
</p>

<p align="center">

Delete Company

Routes : api/company/{id} 
Method : delete

</p>
