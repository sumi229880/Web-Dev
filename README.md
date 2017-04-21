# *******New York Restaurants Inspection Analysis*********
# Food tastes better when you eat with it's quality at BEST!!

[![](https://cldup.com/dTxpPi9lDf.thumb.png)](http://sumeetusturge.com)

#### ABOUT DATASET
This dataset provides restaurant inspections, violations, grades and adjudication information.This data includes the name and location of inactive food service establishments and the violations that were found at the time of the inspection. Inactive food service establishments include only establishments that are no longer in business or have not operated for an extended period of time. Inspections are a “snapshot” in time and are not always reflective of the day-to-day operations and overall condition of an establishment. This dataset is refreshed on a daily basis.

##### Initial observation on data:
  - Notice, lower the SCORE in dataset better the GRADE of the Restaurant.
  - Various violation code and fixes descripiton to particular code.
  - Many columns contains NaN which needs data cleansing.



>The link to the API to get the data from NYC website is:
>https://data.cityofnewyork.us/resource/xx67-kt59.json

#### ANALYSIS # 1

* The cuisine of New York City comprises many cuisines belonging to various ethnic groups that have entered the United States through the city.Almost all ethnic cuisines are well represented in New York City, both within and outside of the various ethnic neighborhoods.New York City was also the founding city of New York Restaurant Week which has spread around the world due to the discounted prices that such a deal offers.
* New York City is called as hub for bussiness and there are thousands of people  entering and leaving the city. With so much of happening in the city, it is highly diversified in its own way and we get wide range of cuisine in the 5 Boroughs of the city.
* What if some one wants to try Italian or Mexican food? Well this analysis is all about finding out the where do we find cuisine which is best in its way and has highest rating when it comes to cleanliness and its quality for food and hygine. Below are the analysis results that I found out. I am sure now you will know where to find the cuisine that you love the most in this city of dreams. 

>Looking at the stats now I exactly know where to find my love for Indian cuisine in NYC without givnig a second thought on the quality. Hope you have found your favourite cuisine. 

#### ANALYSIS # 2

* The cuisine of New York City comprises many cuisines belonging to various ethnic groups that have entered the United States through the city.Almost all ethnic cuisines are well represented in New York City, both within and outside of the various ethnic neighborhoods.New York City was also the founding city of New York Restaurant Week which has spread around the world due to the discounted prices that such a deal offers.
* New York City is called as hub for bussiness and there are thousands of people  entering and leaving the city. With so much of happening in the city, it is highly diversified in its own way and we get wide range of cuisine in the 5 Boroughs of the city.
>Looking at the stats now I exactly know where to find my love for Indian cuisine in NYC without givnig a second thought on the quality. Hope you have found your favourite cuisine.

#### ANALYSIS # 3

* The cuisine of New York City comprises many cuisines belonging to various ethnic groups that have entered the United States through the city.Almost all ethnic cuisines are well represented in New York City, both within and outside of the various ethnic neighborhoods.New York City was also the founding city of New York Restaurant Week which has spread around the world due to the discounted prices that such a deal offers.
* New York City is called as hub for bussiness and there are thousands of people  entering and leaving the city. With so much of happening in the city, it is highly diversified in its own way and we get wide range of cuisine in the 5 Boroughs of the city.
>Looking at the stats now I exactly know where to find my love for Indian cuisine in NYC without givnig a second thought on the quality. Hope you have found your favourite cuisine.


Install the dependencies and devDependencies and start the server.

```sh
$ cd dillinger
$ npm install -d
$ node app
```

For production environments...

```sh
$ npm install --production
$ npm run predeploy
$ NODE_ENV=production node app
```

### Plugins

Dillinger is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md] [PlDb] |
| Github | [plugins/github/README.md] [PlGh] |
| Google Drive | [plugins/googledrive/README.md] [PlGd] |
| OneDrive | [plugins/onedrive/README.md] [PlOd] |
| Medium | [plugins/medium/README.md] [PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md] [PlGa] |


### Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma test
```
#### Building for source
For production release:
```sh
$ gulp build --prod
```
Generating pre-built zip archives for distribution:
```sh
$ gulp build dist --prod
```
### Docker
Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 80, so change this within the Dockerfile if necessary. When ready, simply use the Dockerfile to build the image.

```sh
cd dillinger
docker build -t joemccann/dillinger:${package.json.version}
```
This will create the dillinger image and pull in the necessary dependencies. Be sure to swap out `${package.json.version}` with the actual version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on your host. In this example, we simply map port 8000 of the host to port 80 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart="always" <youruser>/dillinger:${package.json.version}
```

Verify the deployment by navigating to your server address in your preferred browser.

```sh
127.0.0.1:8000
```

#### Kubernetes + Google Cloud

See [KUBERNETES.md](https://github.com/joemccann/dillinger/blob/master/KUBERNETES.md)


### Todos

 - Write MOAR Tests
 - Add Night Mode

License
----

MIT



