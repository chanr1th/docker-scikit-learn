# docker-scikit-learn

Python3 scikit-learn with Jupyter docker image based on alpine 


```
# run Jupyter Notebook container (default password is 123)
docker run -p 8888:8888 -d chanr1th/scikit-learn

# Or use PASSWORD environment variable instead of default
docker run -p 8888:8888 -e PASSWORD=yoursecret -d chanr1th/scikit-learn

# open browser
open http://$(docker-machine ip default):8888
```

**Note:** This image was derived from [smizy/scikit-learn](smizy/scikit-learn) and has modify to work smoother with Windows environment.