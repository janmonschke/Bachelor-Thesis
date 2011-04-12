## REQUEST FLOW COMPARISON

### TRADITIONAL
A HTTP request is matched to the corresponding controller by a router. This controller then triggers the Model-layer to retrieve the necessary data for the request from the underlying database. When the data has been successfully fetched, the controller triggers the View-layer to render the data into the requested View. This data is then being transferred to the browser of the user and the current DOM is replaced with the transferred HTML page.

### SINGLE PAGE
The single-page request-flow is the same as the traditional request-flow until it comes to the rendering of views. Instead of letting the server render a complete new layout and transfer it to the client, the fetched data is serialized into a transport format (JSON, XML...) and the client takes care of rendering the part of the DOM that has changed.
The main differentiation between the two systems is the initial request to the server. In the traditional system you would generate a normal HTML layout and hyperlinks on that page would send GET requests to the server which then would cause a rerendering of the whole page.
In single page web apps the initial request delivers the complete web app and not just a snapshot of it. When the app is initialized a fronted-router takes care of rendering the correct JavaScript view. All requests (e.g. links clicked) will then automatically be passed to the frontend-controller that connects JavaScript Models and JavaScript Views.