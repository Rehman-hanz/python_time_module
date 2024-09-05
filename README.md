# python_time_module
# Small python project using time module

import time

#get current time

current_time = time.ctime()

print("Current time:=", current_time)

#sleep for 10 sec

print("Sleeping for 5 seconds...")

time.sleep(5)

#get current time again

current_time = time.ctime()

print("current time after sleep:", current_time)

#calculate elapsed time

start_time = time.time()

time.sleep(5)

end_time = time.time()

elapsedOtime = end_time - start_time

print("Elapsed time:", elapsedOtime, "Sec")

print("yeaaaaah")




