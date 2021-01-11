# windows–rdp

Ezy setup just some steps

0. Fork it 

1. Signup here if you dont have ngrok account
https://dashboard.ngrok.com

2. Copy token from https://dashboard.ngrok.com

3. Paste that token in settings (in top right of this page) > secrets > New Repository Secret and fill data as.     
        Secrete Name = 'NGROK_AUTH_TOKEN'
        Value = token that you copied in step 2.
        Add Secrete kek.
        
4. Enable github actions https://github.com/features/actions

5. Now open Actions tab on top of this page.

6. Accept whatever it says bla bla.

7. Now change "All Workflows" to "CI".

8. Below that you will see Run Workflow tap on it then again tap on Run Workflow (Green Button).

9. Let it run for 2-3 mins.

10. Open https://dashboard.ngrok.com/status/tunnels 

10. Now copy host address

 ( like x.tcp.ngrok.io.xxxx )

default username : 'jashgro'

default password : 'kthxbye'

11. Enjoy 

All credits to @ElytrA8
