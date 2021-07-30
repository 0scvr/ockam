```yaml
title: Get Started
```

# Build End-to-End Encrypted, Mutually Authenticated, Secure Channels with Ockam

In this step-by-step guide we’ll learn how to build secure messaging channels that
protect en-route messages against eavesdropping, tampering, and forgery.

Data, within modern distributed applications, are rarely exchanged over a single
point-to-point transport connection. Application messages routinely flow over complex,
multi-hop, multi-protocol routes — _across data centers, through queues and caches,
via gateways and brokers_ — before reaching their end destination.

Transport layer security protocols are unable to protect application messages
because their protection is limited by the length and duration of the underlying
transport connection.

Ockam makes it simple for your applications to guarantee end-to-end integrity,
authenticity, and confidentiality of data.

You no longer have to implicitly depend on the security of every other machine or
application within the same network boundary. Instead, your application can have
a strikingly smaller vulnerability surface and easily make granular authorization
decisions about all incoming information and commands.

Let's build mutually-authenticated, end-to-end protected communication between
distributed applications:

<div style="display: none; visibility: hidden;"><hr></div>

<ul>
<li><a href="./00-setup">00. Setup</a></li>
<li><a href="./01-node">01. Node</a></li>
<li><a href="./02-worker">02. Worker</a>
<li><a href="./03-routing">03. Routing</a></li>
<li><a href="./04-routing-many-hops">04. Routing over many hops</a></li>
<li><a href="./05-secure-channel">05. Secure Channel</a></li>
<li><a href="./06-secure-channel-many-hops">06. Secure Channel over many hops</a></li>
<li><a href="./07-routing-over-transport">07. Routing over a transport</a></li>
<li><a href="./08-routing-over-many-transport-hops">08. Routing over many transport hops</a></li>
<li><a href="./09-secure-channel-over-many-transport-hops">09. Secure Channel over many transport hops</a></li>
<li><a href="./10-secure-channel-with-entity">10. Secure Channel with Entity</a></li>
</ul>
