Prerequisite
Install docker-desktop
1. First, clone  and change the directory to the cloned folder 
2. Generate secret certificates and keys
2. In the parent directory of the program, run docker build -t <build name of choice> .
3. Run docker run -d -p 9000:80 -p 9001:443 <your build name of choice>
4. Access the page served through: http://localhost:9000/ and https://localhost:9001/
