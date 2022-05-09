# Room 
* We need some dependencies to use the Room.  
>* **The benefits of the Room :   
>>1. Compile-time verification of SQL queries.  
>>2. Convenience annotations that minimize repetitive and error-prone boilerplate code.  
>>3. Streamlined database migration paths.  

### Primary components
1. The database class that holds the database and serves as the main access point for the underlying connection to your app's persisted data,that is annotated with **@Database**  
2. Data entities that represent tables in your app's database.  
Each Room entity is a class that is annotated with **@Entity**
3. Data access objects (DAOs) that provide methods that your app can use to query, update, insert, and delete data in the database,that is annotated with **@Dao**    

### Define relationships between objects 
1. Intermediate data class: you define a data class that models the relationship between your Room entities.    
2. Multimap return types : you don't need to define any additional data classes.  
  
### Accessing data using Room DAOs 
* Each DAO includes methods that offer abstract access to your app's database. At compile time, Room automatically generates implementations of the DAOs that you define.  
* Room provides convenience annotations for defining methods that perform simple inserts, updates, and deletes without requiring you to write a SQL statement.  
* The **@Query** annotation allows you to write SQL statements and expose them as DAO methods. Use these query methods to query data from your app's database, or when you need to perform more complex inserts, updates, and deletes.  
  

![img](./Room/RoomDB_Transparent.png)  
      
Resources:   
[Overview: Saving data with Room](https://developer.android.com/training/data-storage/room)  
[Defining entities in Room](https://developer.android.com/training/data-storage/room/defining-data)  
[Related entities in Room](https://developer.android.com/training/data-storage/room/relationships)  
[Accessing data with Room](https://developer.android.com/training/data-storage/room/accessing-data#java)