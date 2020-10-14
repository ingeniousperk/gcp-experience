> Name: Sulaiman

> NIM: 10119049

> This readme is made as a prerequisite for joining DSC ITB Student Branch

## Link to the project

It is a web application project made as final project for my CS50x (Harvard) online course using Python (Flask), MySQL, and hosted at **Google Cloud Platform**. It can be found **(here)[https://github.com/ingeniousperk/final-cs50]**.

## Me and GCP

Truthfully I had no prior experience in web deploying when I made the project. In CS50, I learned about basic programming (until data structure) using C, Python, and SQL all using IDE provided by CS50. On the last 2-3 weeks, I took the *web track* and learned HTML, CSS, Javascript, and Flask but only until the point of how to build web locally, in the IDE provided.
That being said, I was freaked out to see how wide-ranged the GCP features are. But the reason why I chose to use GCP is that it's the only easy (administratively) platform. It gives free Rp4.000.000+ credits after sign up and my credit card charged no cent before the credits run out. I didn't have idea how skilled I must be in web development before I used GCP, and that's quite a lot confusing at first. However, the only GCP features used in the project are *App Engine* and *CloudSQL*, because those were what I needed, even I had once heard that *Cloud Functions* and *Compute Engine* also sometimes used in web apps development. So here are my some notable impressions of using App Engine and CloudSQL, in a newcomer's eyes.

New facts that I found in GCP: (some of these may sound silly :laughing:)
* Source files are uploaded from explorer in the editor window. (It takes some time before I can realize this lol)
* GCP doesn't know what language we use to deploy the web, so it needs an *app.yaml* file.
* To install Python libraries just for one project, a *venv* must be created in that project. The libraries can be installed manually or automatically using a *requirements.txt*.
* SQL has its own feature in GCP, namely CloudSQL (contrast with what I did in CS50 IDE, just create a *.db* file inside the explorer)
* After creating the CloudSQL instance, the protocol needs to be included into the *app.yaml*
* Latest version of CloudSQL bills me for usage of 24 hours per day even if my website have no visitor that day. And it cost more than Rp1.000.000 a month for the standard SQL instance.

And new difficulties I found in GCP:
* Can't understand the error reporting and how to debug :cry:
* Don't know how to "preview" the code result, so I deployed it everytime a bit of the code changed.
* I had quite a hard time configuring `pymysql` library to the CloudSQL (thanks to a helpful youtube tutorial).

Overall, I saw GCP has really lots of other advanced functions, but is not quite friendly to a web development newcomer. That's also one reason that I'm excited to join DSC, to explore more of developer stuffs (with Google products) and I can't wait for more projects while I'm in DSC later!

## That's it, thanks! :blush:
