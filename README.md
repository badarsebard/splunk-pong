# Splunk Pong
This is a toy example of using WebAssembly in Splunk. It uses a precompiled wasm module that emulates the classic game of Pong. This proves that possibility for using WebAssembly in Splunk which would allow for incredibly advanced Splunk dashboards. Anything that can be created through C, C++, Go, Rust, and many other languages that are capable of compiling to a WebAssembly target can become dashboard components, dashboards, and even entire pages in Splunk.

# Installation
Copy the `pong` directory into the `apps` directory of your Splunk installation. Navigate to the app to load the dashboard. Control the left padle with `w/s` keys and the right paddle with `up/down` arrows.