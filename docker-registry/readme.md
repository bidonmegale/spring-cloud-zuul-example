docker run -d -p 5000:5000 --restart=always --name registry registry:2
sudo docker tag eurika-machine 192.168.110.21:5000/eurika-machine
sudo docker push 192.168.110.21:5000/eurika-machine



--insecure-registry="192.168.110.21:5000"
