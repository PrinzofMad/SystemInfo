from datetime import datetime, date
import os
import platform
import psutil

version = 1.0
now = datetime.now()
date = date.today()
device = platform.system()
current_time = now.strftime("%H:%M:%S")
cpu = platform.processor()
core = psutil.cpu_count(logical=True)
core2 = psutil.cpu_count(logical=False)

print("|---------------------------------------------------------|")
print("| Version:" , version ,"                                           |")
print("| Profile:", os.environ['USERPROFILE'], "                           |")
print("| Device:", device,"                                        |")
print("| CPU:", cpu," |")
print("| Core Count:", core, "                                          |")
print("| Current Time:" , current_time, "                                 |")
print("| Current Date:" , date, "                               |")
print("|---------------------------------------------------------|")
