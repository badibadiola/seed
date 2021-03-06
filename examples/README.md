## Examples
For specific details see corresponding READMEs.

Consider first looking at [Counter](./counter).

Most of the examples can be run by simply:
```sh
cd examples/$EXAMPLE_DIR
cargo make start
```

### [Homepage repo](https://github.com/seed-rs/seed-rs.org)
The Seed homepage, also serving as an example. Includes simple
interactions, markdown elements, routing, and view markup.

### [Animation Frame](animation_frame)
How to make a basic animation with random generators.

### [AppBuilder](app_builder)
Demonstrates all `AppBuilder`'s methods.

### [Canvas](canvas)
How to make a canvas element and use `ElRef`s.

### [Counter](counter)
Intended as a demo of basic functionality.

### [Counter Advanced](counter_advanced)
Intended as a more sophisticated demo of basic functionality.

### [Drop Zone](drop_zone)
How to create a drop-zone.

### [Mathjax](mathjax)
An example using Mathjax, for LaTeX-like math notation.

### [Orders](orders)
How to perform commands and send messages from `update` function.
And how to use [gloo](https://github.com/rustwasm/gloo) timers.

### [Todo MVC](todomvc)
Classic TodoMVC example with Local Storage.

### [Update from JS](update_from_js)
How to trigger `update` function from Javascript world.
You'll also see how to call JS functions from Rust.

### [UserMedia](user_media)
How to show your webcam output in `video` element.

### [Window Events](window_events)
A demonstration of event-handlers attached to the `window`.

## Server
Backend server integration & interaction examples.

### [Integration](server_integration)
Example of a workspace with [Actix](https://actix.rs/) server.

### [Interaction](server_interaction)
Example of communicating with a server using HTTP requests.

### [Websocket Chat](websocket)
Example of communicating with a server using Websockets.
