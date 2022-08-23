<p align="center">

Add a Company
	<p>Routes : api/company </p>
	<p>Method : post</p>
	<p>i/p    : 
				{
					name: varchar,
					city: varchar,
				}
	</p>
</p>

<p align="center">
Add a User

	<p>Routes : api/users </p>
	<p>Method : post</p>
	<p>i/p    : 
				{
					name: varchar,
					email: varchar,
					phone: varchar
				}
	</p>
</p>

<p align="center">

Allocates a User

	<p>Routes : api/company/{id} </p>
	<p>Method : put</p>
	<p>i/p    : 
				{
					users: int
				}
	</p>
</p>
<p align="center">
List a User

<p>Routes : api/users/</p>
<p>Method : get</p>
</p>

<p align="center">

Delete Company

<p>Routes : api/company/{id} </p>
<p>Method : delete</p>

</p>
