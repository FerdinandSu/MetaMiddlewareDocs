---
sidebar_position: 2
---

# Use Render Caching

To use render caching, you need to make your application distributed first. Please refer to the [Distributed Rendering Documentation](../remote-rendering/distributed) to learn how to split your application.

The parts of the application that don't change much can be cached to avoid repeated rendering: E.g., P1 in the classroom example. Assuming you have the render caching scheduler hosted on http://cache-scheduler/, you can access http://cache-scheduler/swagger to configure the cache scheduling policy for your application.
