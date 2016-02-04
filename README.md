# action-shell-exec

## Action shell script execution for Combodo iTop

1. Install like any other extension. 
   - Copy the action-shell-exec to itop/extensions folder and go to http://localhost/setup/. 
   - Select "Upgrade an existing iTop instance" and follow the wizard.
  
2. Create a new action and link it with triggers. See example below how to pass parameters to the script.

  ![action-shell-script-1.png](images/action-shell-script-1.png)
  
3. The script output will be written to the notification log (see "Notifications" tab in the target object).

  ![action-shell-script-2.png](images/action-shell-script-2.png)

4. Use "Being tested" status in the action and check the notification log to find errors and the command that will be executed.

  ![action-shell-script-3.png](images/action-shell-script-3.png)
  ![action-shell-script-4.png](images/action-shell-script-4.png)
