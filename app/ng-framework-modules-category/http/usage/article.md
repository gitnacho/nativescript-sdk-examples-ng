### HTTP Get

Using the **GET** method by creating a service file to keep the HTTP logic separated from the component file (which does not need to know details on how you fetch the data).

_http-get.service.ts_:

<snippet id='http-get-service'/>

Provide the service in the component. Declare the service (either in the `providers` array of your module/component or by using `provideIn` - learn more about Angular providers [here](https://angular.io/guide/providers)) and inject it in the component's constructor.

_http-get.component.ts_:

<snippet id='http-get-component'/>

### HTTP Post

Using the **POST** method by creating a service file to keep the HTTP logic separated from the component file.

_http-post.service.ts_:

<snippet id='http-post-service'/>

Finally, we can provide our service in our component. Note that the services should be explicitly declared in `providers`
and then should be provided as an argument in our component's constructor.

_http-post.component.ts_:

<snippet id='http-post-component'/>

### HTTP Put

Using the **PUT** method by creating a service file to keep the HTTP logic separated from the component file.

_http-put.service.ts_:

<snippet id='http-put-service'/>

Provide the service in the component (or in the related `NgModule` if the service should be reused).

_http-put.component.ts_:

<snippet id='http-put-component'/>

### HTTP Delete

Using the **DELETE** method by creating a service file to keep the HTTP logic separated from the component file.

_http-delete.service.ts_:

<snippet id='http-delete-service'/>

Provide the service in the component (or in the related `NgModule` if the service should be reused).

_http-delete.component.ts_:

<snippet id='http-delete-component'/>
