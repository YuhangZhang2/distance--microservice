# distance-microservice

---

## Description

distance-microservice the distance is measured by adding zip codes for two cities in the US.

---

## How To Use

Open in your computer

```
git clone https://github.com/YuhangZhang2/distance-microservice.git
```

Go to [zip code api](https://www.zipcodeapi.com/API),
Check out the "API Key" on the website and copy it to the ZIPCODE_API_KEY section of service/distance.js.


```
npm install
```
```
npm start
```

Run successfully at: http://localhost:3000
Next in the test phase.


## Example request

You can query or enter a zip code in Amrican [US Location to Zip Codes](https://www.zipcodeapi.com/API)

A example

creat a web and type ``` http://localhost:3000/distance/97331/90001 ```(example from school to Los Angeles)

It will give you ``` {"distance":779.245} ```

If the address is wrong or out of api range it will output ```{"distance":-1}```
