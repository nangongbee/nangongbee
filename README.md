# Tim Wu

Software Engineer | Backend Systems · AI Systems · Robotics

## About Me

I have spent more than thirteen years building server software, most of it on Linux and much of it in C++. The systems were game servers: a client connects through a gateway, login and game logic are separate services, and platform functions sit beside the core loop rather than inside it.

That work also used Go, Python, Lua, and TypeScript when a service boundary was a better fit than one more C++ process.

I am now studying AI systems and robotics software. Those are current areas of practice. They are not a claim of many years shipping robots or model platforms.

## Engineering Focus

**Backend architecture.** I pay attention to which process owns a session, where a request is allowed to go, and how a failure stays visible instead of disappearing into a helper library.

**Distributed systems.** Login state, cross-service calls, and shared data need an owner. Databases, caches, and messages are part of the design.

**C++ and Linux.** Long-running services have mostly been C++ processes: networking, threading, and the ordinary work of making a server process understandable in production.

**AI systems.** I am learning how a model call fits inside a service: timeouts, a task that can fail in the open, and a pipeline that does not hide a bad result. Notes will be marked as study until there is a public project behind them.

**Real-time communication.** A game gateway and a voice session raise the same kind of question: what is buffered, what is a session, and what happens when the other side disappears.

**Robotics middleware.** ROS 2 is how I am studying robotics software. Simulation comes first. I do not describe that work as a deployed robot.

## Selected Projects

This section stays short on purpose. Forks, empty repositories, and private work are not listed here.

Public write-ups will be added on [wuyingzhen.github.io](https://wuyingzhen.github.io/) when a project is ready to stand on its own.

## Current Interests

- Voice systems, at the level of sessions and protocols
- Intelligent hardware, and the boundary between a device and a service
- Edge computing
- ROS 2
- Robotics software architecture

## Technical Writing

Longer notes live on [wuyingzhen.github.io](https://wuyingzhen.github.io/). The site still holds one archived note from 2019. New posts will be engineering notes: a problem, a design choice, and a conclusion. Learning notes will be labeled as such.

## Contact

[GitHub](https://github.com/wuyingzhen)
