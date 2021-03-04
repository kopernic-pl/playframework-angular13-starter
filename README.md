# Play framework + Angular 10 starter

This is a starter application that shows how Play works. And angular.

## Running

```
cd ng-frontend
npm install -g @angular/cli
npm install
ng build
cd ..
sbt run
```
And then go to http://localhost:9000 to see the running backend application (play framework, still contains and serves some FE for demo purposes).
To see angular part, go to http://localhost:9000/ng

## Controllers

There are several demonstration files available in this template.

- `HomeController.java`:

  Shows how to handle simple HTTP requests.

- `AsyncController.java`:

  Shows how to do asynchronous programming when handling a request.

- `CountController.java`:

  Shows how to inject a component into a controller and use the component when
  handling requests.

## Components

- `Module.java`:

  Shows how to use Guice to bind all the components needed by your application.

- `Counter.java`:

  An example of a component that contains state, in this case a simple counter.

- `ApplicationTimer.java`:

  An example of a component that starts when the application starts and stops
  when the application stops.

## Filters

- `ExampleFilter.java`:

  A simple filter that adds a header to every response.
