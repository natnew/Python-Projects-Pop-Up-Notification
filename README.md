# Python Projects: Pop Up Notification 🐍
Python Script <br>
This repo contains python code that sends you a notification on your computer. <br>
Run the code.

Python
```python
import win10toast
import time


pop = win10toast.ToastNotifier()
pop.show_toast("Notification","Alert!!! Virus Found")

while pop.notification_active():
    time.sleep(1)
```

