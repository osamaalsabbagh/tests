## LARAVEL

#### Q1. Which of the following is not a way to add jobs to a queue in Laravel?

- [ ] Using the dispatch method.
- [ ] Using the dispatchNow method.
- [ ] Using the dispatchLater method.
- [x] Using the dispatchImmediately method.  

<br>

#### Q2. What does the command php artisan queue:restart do in Laravel?


- [ ] Starts a worker process that listens for new jobs on the queue and processes them.  
- [x] Restarts the worker process.  
- [ ] Retries a failed job.  
- [ ] Removes a failed job from the queue.  


<br>

#### Q3. Which of the following is a queue manager in Laravel?

- [x] Horizon  
- [ ] Supervisor  
- [ ] Beanstalkd  
- [ ] Redis  

<br>

#### Q4. Method to create Hash password in laravel?

- [ ] `$hashed = Hash::create('has-text');`.  
- [ ] `$hashed = Hash::all('has-text');`.  
- [x] `$hashed = Hash::make('has-text');`.  
- [ ] None of these.  

<br>

#### Q5. In which directory robots.txt file is located?

- [ ] models 
- [x] public
- [ ] views
- [ ] controller

<br>

#### Q6. Which method breaks the collection into multiple, smaller collections of a given size?

- [x] split()  
- [ ] chunk()  
- [ ] explode() 
- [ ] break()

<br>

#### Q7. Which artisan command is used to remove the compiled class file?

- [x] clear-compiled.  
- [ ] clear compiled.  
- [ ] compiled:clear.  
- [ ] clear:all.  

<br>

#### Q8. Which of following methods are used in database migrations classes?

- [ ] execute() and rollback()  
- [x] up() and down()  
- [ ] run() and delete()  
- [ ] save() and update()  

<br>

#### Q9. How to set a session data in Laravel?

- [ ] `$request->db->session('key', 'value');`.  
- [ ] `$request->session()->set('key', 'value');`.  
- [x] `$request->session()->put('key', 'value');`.  
- [ ] None of These.  

<br>

#### Q10. What is the purpose of the app/Providers directory in a Laravel project?

- [ ] It stores views for the application  
- [ ] It stores controllers for the application
- [ ] It stores routes for the application  
- [x] It stores classes that provide various services to the rest of the application

<br>

#### Q11. How can you create a migration for the failed jobs database table in Laravel?

- [ ] php artisan queue:migrate.  
- [ ] php artisan queue:table.  
- [x] php artisan queue:failed-table.  
- [ ] php artisan queue:create-table.  

<br>

#### Q12. Command to check the status of migration in laravel application?

- [ ] php artisan migration status
- [ ] php artisan status
- [x] php artisan migrate:status   
- [ ] None of these 

<br>

#### Q13. Where are all the Laravel Models stored at?

- [ ] Inside Laravel database  
- [ ] Within a server  
- [x] Main app directory  
- [ ] None of the above  

<br>

#### Q14. What does ORM stands for in laravel?

- [ ] object-related Modifier.  
- [ ] overloaded-relational Mapping.  
- [ ] object-Rotational Mechanisim.  
- [x] object-relational Mapping.  

<br>

#### Q15. In how many ways a new middleware can be register in kernel.php?

- [ ] 1  
- [ ] 2 
- [ ] 3  
- [x] 4
