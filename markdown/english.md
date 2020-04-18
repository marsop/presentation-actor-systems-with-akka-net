---
title: Actor Systems with Akka.net
theme: serif
highlight-theme: github
---

# Actor Systems with Akka.net

Alberto Gregorio

---

## Actor Model

What is an Actor?

----

One Actor can

- receive messages
- process sequentially
- change internal state
- send new messages
- span children

---


# Akka.net

```csharp

namespace Akkanet {
    Actor actor = new Actor(1.2, 1, true, "amigo");
}

```