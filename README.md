# Restaurant API
## Hosted on Heroku

### Test Cases to be run on a command line
##### Check if API is still listening
- curl "https://web422nddrestaurant.herokuapp.com/"
##### Get a single page of restaurant data with 10 items (/api/restaurants?page=#&perPage=#)
- curl "https://web422nddrestaurant.herokuapp.com/api/restaurants?page=1&perPage=10" 
##### Get a single page of restaurant data with 10 items and specific borough (/api/restaurants?page=#&perPage=#&borough=###)
- curl "https://web422nddrestaurant.herokuapp.com/api/restaurants?page=1&perPage=10&borough=Bronx"
##### Get/Put/Delete a single restaurants data (/api/restaurants/:id)
- curl "https://web422nddrestaurant.herokuapp.com/api/restaurants/5eb3d668b31de5d588f4292e"

### Application using API
As the above requests return json data piping it through jq can be done for testing purposes or you may use the link  below to test out a React App that uses this API.
- Link: https://restaurant-react-pearl.vercel.app/
- GitHub Repo: https://github.com/mhdfuhad/restaurantReact
