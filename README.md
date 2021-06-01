# nginx_server_assignment 📢 🗞🗞

## Assignment -

* Deploy the Web assignment on `nginx` server through `docker` and `docker-compose`
* There should be two `containers` one that serves the API and another that serves the frontend
* The API hosting `nginx` should act as a `reverse-proxy` for the API https://newsapi.org/docs/endpoints/everything
* The frontend serving nginx should load the frontend on hitting the root url
* The frontend should fetch the data from the /api route on same server.

## Running -

* To build the containers: ` docker-compose build `
* To run the containers: ` docker-compose up `

## Output -

<table style="width:100%">
  <tr>
    <th><b> Reference Image<b></b></th>
      
  </tr>
  <tr>
    <td><img src="newsapi/images/proxy.PNG"/></td>
  </tr>
</table>
