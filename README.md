# Getting Started

Follow the directions at: 
http://www.mkdocs.org/#installation
to install MKDocs.

Install the extensions (using pip):
```
pip install pygments pymdown-extensions mkdocs-material
```

Clone this repository:
```
git clone https://github.com/istrau2/lupoex-docs
```

# Running the application locally:
```
cd lupoex-docs
mkdocs serve
```

#Deploying

Build with mkdocs:
```
mkdocs build
```

Build a docker image:
```
docker build -t lupoex-docs .
```

Test the docker container locally:
```
docker run -d -p 8080:80 lupoex-docs
```
You should now be able to see the running container at localhost:8080 in your browser.

Finally, push to ecr and deploy.