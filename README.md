# Open_Json-Url-using-Urllib
This code using Urllib to open a url whic contains Json formated dats. Then using json read methode to read the data and itrate through the data to get the count s ath finally made 
the total of that sum by converig to intrger.


======================================== Code  ==================

import urllib
import json
import urllib.request
#Open the urlecode
url ="http://py4e-data.dr-chuck.net/comments_163262.json"
res = urllib.request.urlopen(url)
#js = res.decode()
#print(res)
js = res.read().decode()
print(js)

#Get the Json File
info = json.loads(js)
info = info["comments"]
#print(info)
total = 0

# Itarate through the file and get the count value an sum it
for item in info:
	print("Count: ",item["count"])
	total = total + int(item["count"])
	print("Sum: ", total)
print("Final sum: ", total)
