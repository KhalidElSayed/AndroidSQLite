AndroidSQLite
=============

Android Library Project for SQLite CRUD operations


AndroidSQLite is a well documented library Project intended to simplify the hassle of create, update, delete and 
get operation of Android SQLite database.

Take a look at the following usefull methods that you can try:

			public <T> T add(T entity )
			
			public <T> List<T> addAll (List<T> entities)
			
			public <T> List<T> getAll(T entity, boolean withAllItsListFields)
			
			public <T> T find(T entity, boolean withAllItsListFields)
			
			public int delete(Object entity)
			
			public <T> T update(T entity, boolean withAllItsListFields)
			
			public <T> List<T> updateAll(List<T> entities, boolean withAllItsInnerListFields)
			
			public <T> List<T> findAll(T entity, ContentValues contentValues, boolean withAllItsListFields)	
			
			public <T> List<T> subQuery(T entityToReturn, Object fromEntity, Object whereEntity,  boolean withAllItsListFields)

