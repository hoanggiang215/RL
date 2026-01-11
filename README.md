C:\Users\Admin\PycharmProjects\PythonProject1\.venv\Scripts\python.exe C:\Users\Admin\PycharmProjects\PythonProject1\BFS.py 
*** GRID-BASED RL WITH SEQUENTIAL GOALS ***
============================================================
Choose demo type:
1 - Complete RL training + static visualization
2 - [ANIMATED] Car movement demo (recommended)
Auto-starting animated car movement demo...
This will show the car moving step-by-step to each goal!

*** ANIMATED CAR MOVEMENT DEMO ***
============================================================
This will show the car moving step-by-step to each goal!
Make sure to keep the matplotlib window visible.

Grid: 10×10, Goals: 5, Start: (5, 9)
Training agent for 1000 episodes...
Starting Q-learning training for 1000 episodes...
------------------------------------------------------------
.1f
.1f
.1f
.1f
.1f
.1f
.1f
.1f
.1f
.1f
Training completed!
Total Q-values learned: 1020
.3f
Training completed!

Starting animated evaluation...

*** ANIMATING CAR MOVEMENT ***
Watch the car move step by step to each goal!
Flow: Start → Goal 1 → Reset to Start → Goal 1 becomes black → Goal 2 → Reset → Goal 2 becomes black ...
--------------------------------------------------
   Goal 1 at (0, 1) REACHED → Car was IN goal cell → Now BLACK OBSTACLE
   Reset to Start (5, 9) → Next: Goal 2

   Goal 2 at (7, 2) REACHED → Car was IN goal cell → Now BLACK OBSTACLE
   Reset to Start (5, 9) → Next: Goal 3

   Goal 3 at (2, 4) REACHED → Car was IN goal cell → Now BLACK OBSTACLE
   Reset to Start (5, 9) → Next: Goal 4

   Goal 4 at (2, 6) REACHED → Car was IN goal cell → Now BLACK OBSTACLE
   Reset to Start (5, 9) → Next: Goal 5

   Goal 5 at (9, 8) REACHED → Car was IN goal cell → Now BLACK OBSTACLE
   Reset to Start (5, 9) → Next: Goal 5


================================================================================
*** CONGRATULATIONS! ALL 5 GOALS COMPLETED! ***
================================================================================
[SUCCESS] Total steps taken: 57
[PERFECT] Goals completed: 5/5
[WIN] Agent successfully navigated all sequential goals!
[BLOCKED] All achieved goals are now permanent obstacles!
================================================================================
*** MISSION ACCOMPLISHED! ***
================================================================================

Demo completed! Steps: 57, Goals: 5

Process finished with exit code 0
