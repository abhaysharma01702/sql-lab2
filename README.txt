Steps to execute scripts:

1. Open MySQL Workbench and connect to database.
2. Run CREATE TABLE and INSERT statements to set up the database.
3. Execute each SQL file in the following order:
   - q1.sql
   - q2.sql
   - q3.sql
   - q4.sql
   - q5.sql
4. To test:
   CALL ListAllSubscribers();
   CALL GetWatchHistoryBySubscriber(1);
   CALL AddSubscriberIfNotExists('New User');
   CALL SendWatchTimeReport();
   CALL LoopSubscribersWatchHistory();

Git Repository Link:
(https://github.com/abhaysharma01702/sql-lab2)
