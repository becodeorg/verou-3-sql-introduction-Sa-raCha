# SQL-basics solutions  
### 
### 3. Try the following selects
```
select * from `groups`; 
```

``` 
select name as learner_name, email 
from learners 
where id = 1;
```

### 4. A group needs to be postponed
```
update `groups`
set start_date = '2022-02-14'
where id = 1;
```
```
alter table `groups` 
add status TEXT;
update `groups` 
set status = 'Member of the team got possessed... brb quick exorcism'
where id = 1;
```
