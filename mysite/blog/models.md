			In our blog

			Features
			==========

			Blog will have the following features

			1) Post(Table in database)
			2) Categores(Table in database)
			3) Tag(Table in our database)
			4) Author(Table in our database)


			Let us make a relation between our tables
			==========================================

			1)Post can have many categories, and a categories can have many post( Relation between Post an Category table)(Many to Many relation)

			2)A tag can have many post and a post can have many tag (ManytoMany relation)

			3)auhor can have many posts and a post can have a single author(OneToMany relation) [no post can write by more than authors]

			Attributes for tables
			=====================

			Post
			====
			1 title
			2 created_date
			3 body
			4 tags
			5 categories
			6 autor

			Categories
			==========
			1 cat_name
			2 cat_description

			Author
			======
			1 Author name
			2 Author email (not mandatory)
			3 Author bio

			Tag
			===
			tag_name