# IS-480-580-02-IS-691-01-MERGED-Final_Project
Branden Noack's Final Project (To-Do List)

This bash script will help you create a To-Do List. You will be able to add new agenda items, mark them as complete, and display any tasks that still need to be aaccomplished. Any tasks that are marked as complete willl be built into a file called 'completed'. You will be able to view this file to view all the tasks that have been completed.

Here is how to use this simple program:

1. In order to run it. Save that bash script to your machine.
2. Once saved, navigate to the file location where youy saved it using the Linux Terminal.
3. You will be able to run it by entering the following comands in this order:
  chmod +x Final_Project.txt
  ./Final_Project.txt

  The first command will allow the script to be executed while the second one tells the terminal to run the bash script.
  
4. The first thing that will appear on your screen is a list of 4 options:
    The first option will display your current tasks.
    The second will allow you to add a task.
    The third will allow you to marek one as complete.
    The fourth will exit the program. 

5. If you exit the program, your current tasks will be saved and any items marked as completed will be saved to the file titled 'completed'.

Now lets run through an example. 

This is the very first screen that will appear. From here, lets choose option 2 to add a task.
1. Display To-Do List
2. Add Task
3. Complete Task
4. Exit
Choose an option:

This option will appear for you to add a task. 
Enter task: 

I put 'go to the store' as my task. It will confirm what you typed by presenting this on yuor screen.
Task added: go to the store

Now that I have a task, I chose option 1 in order to show what my list currently has. As you can see, it is showing that I have 'go to the store' under my To-Do List.
Choose an option: 1
To-Do List:
go to the store
1. Display To-Do List
2. Add Task
3. Complete Task
4. Exit

Once I am done with that task, I can choose option 3 to mark a task as completed. The task 'go to the store' is task 1, so I tell it to mark task 1 as completed.
Choose an option: 3
Enter task number to mark as completed: 1
Task marked as completed: 1
1. Display To-Do List
2. Add Task
3. Complete Task
4. Exit

Now that the task 'go to the store' has been completed, I can have it show me my tasks again and see that it is no longer there. That completed task has been moved to the file 'copmleted' incase you want to review your comleted tasks.
Choose an option: 1
To-Do List:
1. Display To-Do List
2. Add Task
3. Complete Task
4. Exit
