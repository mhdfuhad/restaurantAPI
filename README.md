# Restaurant API
## Hosted on Heroku
### Test cases to be run on a command line.
#####  GET /
###### Check if API is still listening
- curl "https://web422nddrestaurant.herokuapp.com/"
##### GET /api/restaurants?page=**num**&perPage=**num**
###### Get a single page of restaurant data with 10 items (page and perPage accept numeric values)
- curl "https://web422nddrestaurant.herokuapp.com/api/restaurants?page=1&perPage=10" 
##### GET /api/restaurants?page=**num**&perPage=**num**&borough=**string** 
###### Get a single page of restaurant data with 10 items and specific borough (borough accepts a string)
- curl "https://web422nddrestaurant.herokuapp.com/api/restaurants?page=1&perPage=10&borough=Bronx"
##### GET/PUT/DELETE /api/restaurants/:id
###### Get/Put/Delete a single restaurants data (GET request example below)
- curl "https://web422nddrestaurant.herokuapp.com/api/restaurants/5eb3d668b31de5d588f4292e"

### Application using API
As the above requests return json data you may use the link  below to test out a React App that uses this API.
- Link: https://restaurant-react-pearl.vercel.app/
- GitHub Repo: https://github.com/mhdfuhad/restaurantReact
