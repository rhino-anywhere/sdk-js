# Javascript SDK
---

## About the Project

**Rhino Anywhere** is a javascript library that allows a clean API interface to listen to, respond to and display a Rhino Viewport stream from a remote Rhino instance.
You can
- Reskin Rhino in any way!
- Control Rhino in any way!
- Interact with Rhino in any way!

## Documentation

The sdk is intended to be used in conjunction with your UI of choice and the RhinoAnywhere plugin. Once you have the plugin running, connect your UI to the plugin by executing:
```
// HTML Video element reference
var viewport = document.getElementById("rhinoViewport");

// RhinoAnywhere Websocket link
var link = "ws://127.0.0.1:8081/" 

// Initialize RhinoAnywhere SDK
let anywhere = new RhinoAnywhere();

// Bind to a video element
anywhere.bind(viewport);

// Connect to RhinoAnywhere
anywhere.connect(link);
```

Once these run, the video element will resize to match Rhino. You can also execute commands:

```
anywhere.sendCommand("Line");
```

## How to Build & Pre-requisites
[Please see building source guide](BUILDSOURCE.md)

## Contributing

See the open issues for a places to help out and get involved.
See the [open issues](https://github.com/rhino-anywhere/rhino-anywhere-frontend/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc) 

## Licensing

Distributed under the MIT license. See `License.md`for more information.

## Acknowledgements

A huge thanks to AEC Tech 2023 for arranging and hosting this event.
Please check out other hackathon projects and future hackathon events hosted by [AECTech](https://www.aectech.us/).
