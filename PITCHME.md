<!-- $theme: default -->

### <span style="color: #1ec15e">Now</span>

Maxis / Nov. 22

---

### What is Now?

- Now allows you to take your JavaScript (Node.js) or Docker powered websites, applications and services to the cloud.

- Any directory that contains a <span style="color: #1ec15e">package.json</span> or <span style="color: #1ec15e">Dockerfile</span> can be transported to the cloud with one command: <span style="color: #1ec15e">now</span>.

---

### Features

- Easy
- Unlimited
- Realtime
- Scaling
- View Source

+++

### Features

- Easy

<pre>
> no need to install git
> no need to setup tokens
> no cloud provider setup
</pre>

- Unlimited
- Realtime
- Scaling
- View Source

+++

### Features

- Easy
- Unlimited

<pre>
> No need to remove old ones
> URLs stay around forever
</pre>

- Realtime
- Scaling
- View Source

+++

### Features

- Easy
- Unlimited
- Realtime

<pre>
> console in browser
</pre>

- Scaling
- View Source

+++
### Features

- Easy
- Unlimited
- Realtime
- Scaling

<pre>
> Dynamic
> Multi-cloud
</pre>

- View Source

+++

#### Why not AWS Lambda / Azure Functions / Google Cloud Functions?

- Exposing Just a Function Is Not Enough (?)
- ad-hoc response codec
- HTTP/2

---

### magic `_src`

https://hello-next-hcegtfqzka.now.sh/_src

---

### Now vs Heroku

|  | Now | Heroku
| --- | --- | --- |
| setup | `npm install` | `heroku cli` (`npm`) |
| deployment speed | 1:50.70 | 39.46 |
| localhost? | yes | no |

---

<https://secure-atoll-72955.herokuapp.com/>

<https://hello-next-hcegtfqzka.now.sh/>

---

micro-services with now.sh

<pre>
{
  "rules": [
    { "pathname": "/api/*", "dest": "comp-test-api.now.sh" },
    { "pathname": "/**", "dest": "comp-test-frontend.now.sh" },
    { "dest": "www.comp-test.now.sh" }
  ]
}
</pre>

<small>
reference: <a>https://medium.com/@littleStudent/cors-and-micro-services-with-now-sh-a805708a4e93</a>
</small>